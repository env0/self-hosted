# Customizing env0 agent using Kustomize and Helm Post Render hooks
The env0 agent externalize an a wide array of values that may be set to configure the agent.  
We do our best to support all common configuration case-scenarios, but sometimes a more exotic or pre-released configuration is required.  
For such advanced cases, we offer this reference example of utilizing [kustomize](https://kustomize.io/) alongside [Helm Post Rendering](https://helm.sh/docs/topics/advanced/#post-rendering) to further customize our chart.  

## Prerequisites
- `kustomize` 3.5+ installed in your `PATH`
- A running Kubernetes cluster
- Helm 3.1+

## The example
This patches the resource limits of the `agent-trigger` deployment.  

## Running the example

```shell
# Add the env0 repo if you haven't already
helm repo add env0 https://env0.github.io/self-hosted
helm repo update

# Install the env0 chart
helm upgrade --install --create-namespace env0-agent env0/env0-agent --namespace env0-agent \
-f <your_agent_key>_values.yaml -f values.customer.yaml \
--post-renderer ./kustomize-agent
```

## Modifying the example
You may change the `kustomization.yaml` to target and patch the resources you wish to patch on the env0 agent installation.  

