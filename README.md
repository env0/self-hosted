# env0 Agent - Helm Chart
This is a Helm Chart repository for installing env0 agent on your Kubernetes cluster.  

## Prerequisites
- A Kubernetes cluster with autoscaler and Persistent Volume. You may use our `prerequisites` stack to deploy an EKS based solution to your AWS account, or setup your own compatible cluster elsewhere.  
- A dedicated `values.yaml` file provided to you by env0 - this file holds your key and secret to integrate your agent with env0.  
  Please see our [Business tier pricing](https://www.env0.com/pricing) and contact us to obtain the file for your agent.    
  
## Installation
1. Add our Helm Repo
```shell
helm repo add env0-agent https://env0.github.io/self-hosted
```

2. Update Helm Repo
```shell
helm repo update
```

3. Install the Helm Chart
```shell
helm install env0-agent env0/env0-agent --version 1.0.0 --namespace env0-keda
```
