
<br />
## v3.0.72


- Chore: Update agent-chart readme @liranfarage89 (#7381)<br />
## v3.0.80


- Chore add waf 2 @alonnoga (#7445)<br />
## v3.0.91


- chore: add Server Side Encryption to SQS and SNS @omry-hay (#7643)<br />
## v3.0.137


- Fix: Send xStarted events to FIFO topic + retry them @avnerenv0 (#8034)<br />
## v3.0.143


- chore support big plans @alonnoga (#8227)<br />
## v3.0.148


- Chore: Adjust Agent for working behind a proxy @roni-frantchi (#8371)<br />
## v3.0.152


- Add Vault details to SHAG @eranelbaz (#8455)<br />
## v3.0.154


- Fix: revert home mount @HeverFarber (#8501)<br />
## v3.0.156


- Harden pods - runAsNonRoot @roni-frantchi (#8476)
- Feat add vault secret fetching @Wassap124 (#8462)<br />
## v3.0.167


- KEDA agent cleanup - remove podHistory @chpl (#8672)<br />
## v3.0.172


- Feat: OIDC token (JWT) new lambda for Vault CLI integration @razbensimon (#8698)<br />
## v3.0.191


- chore - exposing DNS record for each of our agents @eladmosh (#8833)<br />
## v3.0.194


- fix - after adding DNS for API GW PRs envs occasionally throw error  @eladmosh (#8903)<br />
## v3.0.194


- fix - after adding DNS for API GW PRs envs occasionally throw error  @eladmosh (#8903)<br />
## v3.0.197


- change module-reader to deployment-servie organization-role type @Wassap124 (#8870)<br />
## v3.0.204


- Chore: switch lambda invocation before deletion @Wassap124 (#8984)<br />
## v3.0.206


- Chore: Hard-coded dockerImages in agent-chart @liranfarage89 (#8861)<br />
## v3.0.222


- Chore: Make proxy vars in k8s yamls conditional @avnerenv0 (#9410)<br />
## v3.0.224


- Fix: Empty values in generated values.yaml overrides user's custom values when  @roni-frantchi (#9456)&nbsp;
## v3.0.230
- Stability Improvement&nbsp;
## v3.0.246


- Chore: increase agent trigger liveness probe timeout @yaronya (#9692)&nbsp;
## v3.0.258


- Fix: reduce apiGW lambda permissions to per stage @liranfarage89 (#9894)
- Fix: add an explicit dependency between API GW usage plan and API GW stage @yaronya (#9890)&nbsp;
## v3.0.293


- Feat : Allow adding custom certificates to our agent @razbensimon (#10195)&nbsp;
## v3.0.298


- Chore: Node does not pickup on Custom CA certificats @avnerenv0 (#10434)&nbsp;
## v3.0.306


- FEAT: create download code step @tomer-landesman (#10388)&nbsp;
## v3.0.313


- Chore: change download configuration version code logic to use s3 signed url (WIP feature) @ronnyorot (#10559)&nbsp;
## v3.0.321


- Chore: add remote run tables tf and attributes @ItamarMalka (#10713)&nbsp;
## v3.0.324


- Chore: Fix remote run tables resources deletion @ItamarMalka (#10767)&nbsp;
## v3.0.325
- Stability Improvement&nbsp;
## v3.0.351
- Stability Improvement&nbsp;
## v3.0.355


- Fix: deployment service API GW deployment @yaronya (#11099)&nbsp;
## v3.0.358


- Chore: warm pods @yaronya (#11054)&nbsp;
## v3.0.359


- Fix - apply network policy only to the env0 pods @chpl (#11169)&nbsp;
## v3.0.371


- chore: Use new crypto common in deployment service @orr-levinger (#11302)&nbsp;
## v3.0.378


- Chore kms configuration @orr-levinger (#11357)&nbsp;
## v3.0.381


- feat-remove-unneeded-encryption-permissions-from-self-hosted-agent-gateways @tomporat247 (#11392)&nbsp;
## v3.0.382


- feat-remove-old-crypto-leftovers @tomporat247 (#11410)&nbsp;
## v3.0.382


- feat-remove-old-crypto-leftovers @tomporat247 (#11410)&nbsp;
## v3.0.399


- Chore - handle kms 4096 bytes limit @chpl (#11536)&nbsp;
## v3.0.414


- Fix: copy homedir content to the mounted volume @chpl (#11756)&nbsp;
## v3.0.416


- Fix - set security context for the init container @chpl (#11797)
- Chore: Fix gitlab enterprise base url suffix helm parameter name @ItamarMalka (#11794)
- chore: add deployment affinity helm value @orr-levinger (#11772)&nbsp;
## v3.0.419


- feat-empty-helm-deployment-handler @tomporat247 (#11825)&nbsp;
## v3.0.444
- Stability Improvement&nbsp;
## v3.0.452


- Fix: Self-hosted agent running with RO root FS has empty home dir @chpl (#12321)&nbsp;
## v3.0.458
- Stability Improvement&nbsp;
## v3.0.459


- Chore: set deployment queue message timeout @yaronya (#12425)&nbsp;
## v3.0.473
- Stability Improvement&nbsp;
## v3.0.475


- feat: use enctyption-key to read state by decrypting @yarivg (#12565)
- feat: use ENV0_STATE_ENCRYPTION_KEY to encrypt uploaded state. @igalklebanov (#12559)
- Chore: Update helm chart readme @yaronya (#12586)&nbsp;
## v3.0.481


- feat docker agent env file @alonnoga (#12556)&nbsp;
## v3.0.488


- Chore: add new IAM access key and API GW key to TF agent stack @yaronya (#12731)&nbsp;
## v3.0.495
- Stability Improvement&nbsp;
## v3.0.497


- Chore docker agent pr improvments @GiliFaroEnv0 (#12763)&nbsp;
## v3.0.501


- return s3 permissions for saas for warm pods @alonnoga (#12817)
- chore change s3 state path and limit access per stage @alonnoga (#12758)&nbsp;
## v3.0.505


- Chore: Upgrade  prerequisites EKS cluster @liranfarage89 (#12726)
- Feat: create new SaaS agent on new EKS cluster, same Persistent Volume @liranfarage89 (#12769)
- chore remove saas s3 access @alonnoga (#12824)&nbsp;
## v3.0.505


- Chore: Upgrade  prerequisites EKS cluster @liranfarage89 (#12726)
- Feat: create new SaaS agent on new EKS cluster, same Persistent Volume @liranfarage89 (#12769)
- chore remove saas s3 access @alonnoga (#12824)&nbsp;
## v3.0.510
- Stability Improvement&nbsp;
## v3.0.510
- Stability Improvement&nbsp;
## v3.0.514


- Chore: Add  New Chart Config: Logger (format, level), Proxy-limits, imagePullPolicy @liranfarage89 (#12929)&nbsp;
## v3.0.515


- chore add lumigo logging @amit-alkobi-env0 (#12948)&nbsp;
## v3.0.520


- Chore: Allow configuring agent proxy's log level and log forma @GiliFaroEnv0 (#13021)&nbsp;
## v3.0.522


- Enable delete protection on all DDB tables @roni-frantchi (#13042)&nbsp;
## v3.0.522


- Enable delete protection on all DDB tables @roni-frantchi (#13042)&nbsp;
## v3.0.525


- Remove iac references to crypto password @weinguy-env0 (#13090)&nbsp;
## v3.0.525


- Remove iac references to crypto password @weinguy-env0 (#13090)&nbsp;
## v3.0.526


- Chore: Allow configuring agent proxy's resources request @GiliFaroEnv0 (#13108)&nbsp;
## v3.0.529


- Fix: Agent Helm chart typo causes @roni-frantchi (#13148)&nbsp;
## v3.0.530


- Fix: Helm chart installation fails when providing proxy resources.requests @roni-frantchi (#13149)&nbsp;
## v3.0.535


- Chore : remove epsagon @GiliFaroEnv0 (#13131)&nbsp;
## v3.0.535


- Chore : remove epsagon @GiliFaroEnv0 (#13131)&nbsp;
## v3.0.547


- Add API key id as agent gateway stack output @roni-frantchi (#13301)&nbsp;
## v3.0.547


- Add API key id as agent gateway stack output @roni-frantchi (#13301)&nbsp;
## v3.0.558


- CHORE: change agent GW domain to regional API @tomer-landesman (#13449)&nbsp;
## v3.0.558


- CHORE: change agent GW domain to regional API @tomer-landesman (#13449)&nbsp;
## v3.0.560


- Chore: migrate agent-related DDB tables to be global @yaronya (#13360)
- Add active-region table @roni-frantchi (#13455)
- Add active region endpoint for agent @roni-frantchi (#13472)&nbsp;
## v3.0.561


- Chore: Add agent support for efs-csi-driver static provisioning @ronnyorot (#13456)
- Fix: shorter names for agent-related IAM resources @yaronya (#13494)
- Stability Improvements @yaronya (#13482)&nbsp;
## v3.0.561


- Chore: Add agent support for efs-csi-driver static provisioning @ronnyorot (#13456)
- Fix: shorter names for agent-related IAM resources @yaronya (#13494)
- Stability Improvements @yaronya (#13482)&nbsp;
## v3.0.565


- Chore - API GW and SaaS agent in secondary region @chpl (#13533)&nbsp;
## v3.0.565


- Chore - API GW and SaaS agent in secondary region @chpl (#13533)&nbsp;
## v3.0.568


- Chore: custom domain names for DR @yaronya (#13582)&nbsp;
## v3.0.571
- Stability Improvement&nbsp;
## v3.0.573


- Chore - make TF plan of the GW faster @chpl (#13696)
- fix: 11230 exclude saas agent from active region check @amit-alkobi-env0 (#13625)&nbsp;
## v3.0.576


- Chore: support weighted DNS @yaronya (#13638)&nbsp;
## v3.0.579


- Chore: remove old KMS key @yaronya (#13724)&nbsp;
## v3.0.580


- Chore - fixes for deploying services to prod dr @chpl (#13762)&nbsp;
## v3.0.584


- Chore - no warm pods in the secondary region @chpl (#13846)&nbsp;
## v3.0.589
- Stability Improvement&nbsp;
## v3.0.599


- Fix: possible agent list modification deadlock @yaronya (#13992)&nbsp;
## v3.0.607
- Stability Improvement&nbsp;
## v3.0.611
- Stability Improvement&nbsp;
## v3.0.611
- Stability Improvement&nbsp;
## v3.0.620
- Stability Improvement&nbsp;
## v3.0.621


- Chore: revert API GW cache for agents APIs @yaronya (#14186)&nbsp;
## v3.0.623


- Chore - jobHistoryLimit defaults in the values.yaml @chpl (#14204)
- Fix: API gateway no integration defined @Yossi-kerner (#14182)&nbsp;
## v3.0.631


- Feature: allow using User-Managed identity for Azure @sagilaufer1992 (#14270)&nbsp;
## v3.0.640


- Chore: Add karpenter do-not-evict annotation for scaled-job @avnerenv0 (#14461)&nbsp;
## v3.0.646


- Add additional annotations and env vars to values @roni-frantchi (#14507)&nbsp;
## v3.0.650


- Chore: helm agent annotations @away168 (#14529)&nbsp;
## v3.0.650


- Chore: helm agent annotations @away168 (#14529)&nbsp;
## v3.0.652


- Chore - delete kinesis @weinguy-env0 (#14467)&nbsp;
## v3.0.663


- Chore - stricter security context @chpl (#14696)&nbsp;
## v3.0.673


- chore: fix quoting logic for additional env vars @away168 (#14784)&nbsp;
## v3.0.673


- chore: fix quoting logic for additional env vars @away168 (#14784)&nbsp;
## v3.0.673


- chore: fix quoting logic for additional env vars @away168 (#14784)&nbsp;
## v3.0.683


- feat: add secrets and secret mounts @away168 (#14903)&nbsp;
## v3.0.686


- feat add helm config for provider caching ( network mirror in tfrc ) @alonnoga (#14828)&nbsp;
## v3.0.686


- feat add helm config for provider caching ( network mirror in tfrc ) @alonnoga (#14828)&nbsp;
## v3.0.689


- Feat: Vault OIDC authentication for secrets @liranfarage89 (#14920)&nbsp;
## v3.0.703


- Fix: Add kubernetes path to login @liranfarage89 (#15150)&nbsp;
## v3.0.706


- Feat: Handle multiple approval policies in deployment @liranfarage89 (#15163)

&nbsp;
## v3.0.706


- Feat: Handle multiple approval policies in deployment @liranfarage89 (#15163)&nbsp;
## v3.0.722


- add helm value to encrypt sensitive values @eranelbaz (#15355)&nbsp;
## v3.0.724


- encrypt terraform outputs if the user opt-in @eranelbaz (#15360)&nbsp;
## v3.0.724


- encrypt terraform outputs if the user opt-in @eranelbaz (#15360)&nbsp;
## v3.0.724


- encrypt terraform outputs if the user opt-in @eranelbaz (#15360)&nbsp;
## v3.0.724


- encrypt terraform outputs if the user opt-in @eranelbaz (#15360)&nbsp;
## v3.0.730


- Chore - ability to use custom UID for the agent @chpl (#15477)&nbsp;
## v3.0.730


- Chore - ability to use custom UID for the agent @chpl (#15477)&nbsp;
## v3.0.745


- chore: add pvc storage configuration request @away168 (#15496)&nbsp;
## v3.0.745


- chore: add pvc storage configuration request @away168 (#15496)&nbsp;
## v3.0.745


- chore: add pvc storage configuration request @away168 (#15496)&nbsp;
## v3.0.745


- chore: add pvc storage configuration request @away168 (#15496)&nbsp;
## v3.0.750


- Chore: Update agent RBAC @away168 (#15722)&nbsp;
## v3.0.750


- Chore: Update agent RBAC @away168 (#15722)&nbsp;
## v3.0.755


- Allow passing/overriding values.yaml secrets via user defined K8s secret @roni-frantchi (#15794)&nbsp;
## v3.0.755


- Allow passing/overriding values.yaml secrets via user defined K8s secret @roni-frantchi (#15794)&nbsp;
## v3.0.757


- StateEncryptionKey can be found in K8S Secret @sagydr (#15827)&nbsp;
## v3.0.757


- StateEncryptionKey can be found in K8S Secret @sagydr (#15827)&nbsp;
## v3.0.757


- StateEncryptionKey can be found in K8S Secret @sagydr (#15827)&nbsp;
## v3.0.770


- Fix - treat the env vars from k8s secrets as sensitive vars @chpl (#15907)&nbsp;
## v3.0.770


- Fix - treat the env vars from k8s secrets as sensitive vars @chpl (#15907)&nbsp;
## v3.0.776
- Stability Improvement&nbsp;
## v3.0.776
- Stability Improvement&nbsp;
## v3.0.790


- make cpu limits optional @away168 (#15793)&nbsp;
## v3.0.790


- make cpu limits optional @away168 (#15793)&nbsp;
## v3.0.790


- make cpu limits optional @away168 (#15793)&nbsp;
## v3.0.791


- Chore: runAsUser and runAsGroup as Int @away168 (#15750)&nbsp;
## v3.0.791


- Chore: runAsUser and runAsGroup as Int @away168 (#15750)&nbsp;
## v3.0.796


-  CHORE: remove tofu versions token from docker image @tomer-landesman (#16236)&nbsp;
## v3.0.796


-  CHORE: remove tofu versions token from docker image @tomer-landesman (#16236)&nbsp;
## v3.0.804


- feat: add InitContainer / Custom Volume Mount @away168 (#15938)&nbsp;
## v3.0.832


- Chore: Update karpenter annotation to new key @avnerenv0 (#16537)&nbsp;
## v3.0.832


- Chore: Update karpenter annotation to new key @avnerenv0 (#16537)&nbsp;
## v3.0.833


- Fix: Agent http proxy OOM @avnerenv0 (#16593)&nbsp;
## v3.0.833


- Fix: Agent http proxy OOM @avnerenv0 (#16593)&nbsp;
## v3.0.839


- feat use oidc for aws ssm @alonnoga (#16330)
- Chore: Sunset EFS - Part 2 @yaronya (#16656)&nbsp;
## v3.0.839


- feat use oidc for aws ssm @alonnoga (#16330)
- Chore: Sunset EFS - Part 2 @yaronya (#16656)&nbsp;
## v3.0.839


- feat use oidc for aws ssm @alonnoga (#16330)
- Chore: Sunset EFS - Part 2 @yaronya (#16656)&nbsp;
## v3.0.839


- feat use oidc for aws ssm @alonnoga (#16330)
- Chore: Sunset EFS - Part 2 @yaronya (#16656)&nbsp;
## v3.0.851


- Chore: support deployment toleration @Wassap124 (#16791)&nbsp;
## v3.0.851


- Chore: support deployment toleration @Wassap124 (#16791)&nbsp;
## v3.0.854


- Chore: Agent Helm Chart - add resource contraints to initcontainer @GiliFaroEnv0 (#16799)&nbsp;
## v3.0.854


- Chore: Agent Helm Chart - add resource contraints to initcontainer @GiliFaroEnv0 (#16799)&nbsp;
## v3.0.858


- Chore: Allow override OIDC SSM credentials for SHAG @GiliFaroEnv0 (#16830)&nbsp;
## v3.0.867


- FEAT: add GetSensitiveVariables lambda for agent @tomer-landesman (#16907)
- Chore: Add k8s version logs @yaronya (#16929)&nbsp;
## v3.0.867


- FEAT: add GetSensitiveVariables lambda for agent @tomer-landesman (#16907)
- Chore: Add k8s version logs @yaronya (#16929)&nbsp;
## v3.0.873


- Chore: Improve agent proxy ability to handle high load @chpl (#16947)&nbsp;
## v3.0.873


- Chore: Improve agent proxy ability to handle high load @chpl (#16947)&nbsp;
## v3.0.876


- Chore: add new agentImagePullSecretRef helm value @yaronya (#17022)&nbsp;
## v3.0.876


- Chore: add new agentImagePullSecretRef helm value @yaronya (#17022)&nbsp;
## v3.0.876


- Chore: add new agentImagePullSecretRef helm value @yaronya (#17022)&nbsp;
## v3.0.877


- Chore: Remove unused agent_image_pull_secret TF var @yaronya (#17048)&nbsp;
## v3.0.877


- Chore: Remove unused agent_image_pull_secret TF var @yaronya (#17048)&nbsp;
## v3.0.887
- Stability Improvement&nbsp;
## v3.0.887
- Stability Improvement&nbsp;
## v3.0.892


- Chore: Change k8s CronJob api to batch/v1 @yaronya (#17236)&nbsp;
## v3.0.892


- Chore: Change k8s CronJob api to batch/v1 @yaronya (#17236)&nbsp;
## v3.0.892


- Chore: Change k8s CronJob api to batch/v1 @yaronya (#17236)&nbsp;
## v3.0.892


- Chore: Change k8s CronJob api to batch/v1 @yaronya (#17236)&nbsp;
## v3.0.915
- Stability Improvement&nbsp;
## v3.0.915
- Stability Improvement&nbsp;
## v3.0.933
- Stability Improvement&nbsp;
## v3.0.933
- Stability Improvement&nbsp;
## v3.0.933
- Stability Improvement&nbsp;
## v3.0.942


- feat - support passphrase for Vault login @tomporat247 (#17646)&nbsp;
## v3.0.942


- feat - support passphrase for Vault login @tomporat247 (#17646)&nbsp;
## v3.0.944


- Chore: add ignore ssl in proxy pod @ItamarMalka (#17722)&nbsp;
## v3.0.960


- Chore change table class of dynamodb @omry-hay (#17815)&nbsp;
## v3.0.960


- Chore change table class of dynamodb @omry-hay (#17815)&nbsp;
## v3.0.960


- Chore change table class of dynamodb @omry-hay (#17815)&nbsp;
## v3.0.969


- Feat: Create UpdateStateResources Lambda stub @liranfarage89 (#17873)&nbsp;
## v3.0.969


- Feat: Create UpdateStateResources Lambda stub @liranfarage89 (#17873)&nbsp;
## v3.0.969


- Feat: Create UpdateStateResources Lambda stub @liranfarage89 (#17873)&nbsp;
## v3.0.969


- Feat: Create UpdateStateResources Lambda stub @liranfarage89 (#17873)&nbsp;
## v3.0.970


- Chore: Add OCI helm values @ItamarMalka (#17885)&nbsp;
## v3.0.970


- Chore: Add OCI helm values @ItamarMalka (#17885)&nbsp;
## v3.0.970


- Chore: Add OCI helm values @ItamarMalka (#17885)&nbsp;
## v3.0.978


- Chore: state resource calculate compass id @HeverFarber (#17951)&nbsp;
## v3.0.978


- Chore: state resource calculate compass id @HeverFarber (#17951)&nbsp;
## v3.0.978


- Chore: state resource calculate compass id @HeverFarber (#17951)&nbsp;
## v3.0.978


- Chore: state resource calculate compass id @HeverFarber (#17951)&nbsp;
## v3.0.985


- Chore: Remove CRON_JOB_API from agent trigger pod @yaronya (#18019)&nbsp;
## v3.0.985


- Chore: Remove CRON_JOB_API from agent trigger pod @yaronya (#18019)&nbsp;
## v3.0.987


- Chore: Add CA certificates to the trigger pod @RLRabinowitz (#18027)
- Chore: module usage - resolve modules @sagilaufer1992 (#17956)&nbsp;
## v3.0.998


- Chore: support multiple install ids for GHE @HeverFarber (#18104)&nbsp;
## v3.0.998


- Chore: support multiple install ids for GHE @HeverFarber (#18104)&nbsp;
## v3.0.1006
- Stability Improvement&nbsp;
## v3.0.1006
- Stability Improvement&nbsp;
## v3.0.1006
- Stability Improvement&nbsp;
## v3.0.1006
- Stability Improvement&nbsp;
## v3.0.1006
- Stability Improvement&nbsp;
## v3.0.1009


- Add agent additional env vars @eranelbaz (#18247)&nbsp;
## v3.0.1009


- Add agent additional env vars @eranelbaz (#18247)&nbsp;
## v3.0.1010


- Chore: load primary region state once to avoid tf plan failures @ItamarMalka (#18211)&nbsp;
## v3.0.1010


- Chore: load primary region state once to avoid tf plan failures @ItamarMalka (#18211)&nbsp;
## v3.0.1010


- Chore: load primary region state once to avoid tf plan failures @ItamarMalka (#18211)&nbsp;
## v3.0.1010


- Chore: load primary region state once to avoid tf plan failures @ItamarMalka (#18211)&nbsp;
## v3.0.1012


- Chore: Add custom env0 labels to the deployment pod @yaronya (#18273)&nbsp;
## v3.0.1013


- Chore add an endpoint to update the deployment log from the agent @alonnoga (#18266)&nbsp;
## v3.0.1013


- Chore add an endpoint to update the deployment log from the agent @alonnoga (#18266)&nbsp;
## v3.0.1013


- Chore add an endpoint to update the deployment log from the agent @alonnoga (#18266)&nbsp;
## v3.0.1021


- Chore: rotate assumer access key @Wassap124 (#18393)&nbsp;
## v3.0.1021


- Chore: rotate assumer access key @Wassap124 (#18393)&nbsp;
## v3.0.1021


- Chore: rotate assumer access key @Wassap124 (#18393)&nbsp;
## v3.0.1024
- Stability Improvement&nbsp;
## v3.0.1024
- Stability Improvement&nbsp;
## v3.0.1027


- Chore add lambda to get last apply deployment data in agent @alonnoga (#18449)&nbsp;
## v3.0.1044


- Chore: Add manage-pull-request lambda @sagydr (#18578)&nbsp;
## v3.0.1053


- Chore: Adding new GetGitToken lambda accessible from the GW @sagydr (#18653)&nbsp;
## v3.0.1058


- Chore: Invoke AI model thru built in prompts @sagydr (#18692)&nbsp;
## v3.0.1058


- Chore: Invoke AI model thru built in prompts @sagydr (#18692)&nbsp;
## v3.0.1058


- Chore: Invoke AI model thru built in prompts @sagydr (#18692)&nbsp;
## v3.0.1074


- Add configuration that allows the user to block all destroy and task commands in the agent @yarden-fishler-dev (#18852)&nbsp;
## v3.0.1074


- Add configuration that allows the user to block all destroy and task commands in the agent @yarden-fishler-dev (#18852)&nbsp;
## v3.0.1074


- Add configuration that allows the user to block all destroy and task commands in the agent @yarden-fishler-dev (#18852)&nbsp;
## v3.0.1082


- Fix: use a different PVC mount for the cache @GiliFaroEnv0 (#18890)&nbsp;
## v3.0.1082


- Fix: use a different PVC mount for the cache @GiliFaroEnv0 (#18890)&nbsp;
## v3.0.1093


- add to missed value to schema json @eranelbaz (#19028)&nbsp;
## v3.0.1114


- Chore - additionalPodConfig on agent-proxy and agent-trigger @chpl (#19188)&nbsp;
## v3.0.1128
- Stability Improvement&nbsp;
## v3.0.1128
- Stability Improvement&nbsp;
## v3.0.1141


- Chore: change deployment timeout to 1 hour @HeverFarber (#19379)&nbsp;
## v3.0.1141


- Chore: change deployment timeout to 1 hour @HeverFarber (#19379)&nbsp;
## v3.0.1141


- Chore: change deployment timeout to 1 hour @HeverFarber (#19379)&nbsp;
## v3.0.1141


- Chore: change deployment timeout to 1 hour @HeverFarber (#19379)&nbsp;
## v3.0.1159


- Chore: Make API GW of SaaS in prod regional @Yossi-kerner (#19529)&nbsp;
## v3.0.1159


- Chore: Make API GW of SaaS in prod regional @Yossi-kerner (#19529)&nbsp;
## v3.0.1159


- Chore: Make API GW of SaaS in prod regional @Yossi-kerner (#19529)&nbsp;
## v3.0.1160
🚨 Important Change

Starting with this version, deployments will automatically download and install any required tools during runtime.
You no longer need to rely on preinstalled binaries.

Examples:
* Kubernetes users: kubectl (and helm if needed) will be installed automatically.
* CloudFormation users: the AWS CLI will be downloaded as part of the deployment.
* Most IaC tools (such as Terraform) are not affected, since they already download the required versions during runtime.

🔮 Coming Soon

In the next release, no tools will be preinstalled by default.
We’ll share a detailed update well in advance.
&nbsp;
## v3.0.1160


- ENG-129 Halt the deployment and do not upload working dir when we had an issue with fetching the last working dir @Yossi-kerner (#19544)
- Chore: Read and Write ORG secrets to both Secret Manager and DDB with fallback @chpl (#19533)
- eng 177 deployment should be consumed evenly from sqs @yarivg (#19551)
- eng-198: Install packages on demend @HeverFarber (#19477)&nbsp;
## v3.0.1160


- ENG-129 Halt the deployment and do not upload working dir when we had an issue with fetching the last working dir @Yossi-kerner (#19544)
- Chore: Read and Write ORG secrets to both Secret Manager and DDB with fallback @chpl (#19533)
- eng 177 deployment should be consumed evenly from sqs @yarivg (#19551)
- eng-198: Install packages on demend @HeverFarber (#19477)&nbsp;
## v3.0.1160


- ENG-129 Halt the deployment and do not upload working dir when we had an issue with fetching the last working dir @Yossi-kerner (#19544)
- Chore: Read and Write ORG secrets to both Secret Manager and DDB with fallback @chpl (#19533)
- eng 177 deployment should be consumed evenly from sqs @yarivg (#19551)
- eng-198: Install packages on demend @HeverFarber (#19477)&nbsp;
## v3.0.1163


- eng-284: Deployment Image v4.0.0 @HeverFarber (#19555)&nbsp;
## v3.0.1163


- eng-284: Deployment Image v4.0.0 @HeverFarber (#19555)&nbsp;
## v3.0.1167


- ENG-75 - Add tag based retention @eranelbaz (#19603)&nbsp;
## v3.0.1167


- ENG-75 - Add tag based retention @eranelbaz (#19603)&nbsp;
## v3.0.1167


- ENG-75 - Add tag based retention @eranelbaz (#19603)&nbsp;
## v3.0.1172


- fix: resolve helm schema validation errors on newer versions @alonnoga (#19699)&nbsp;
## v4.0.0
🚨 Breaking Changes

Starting with this version, no tools will be preinstalled by default.
This change may affect your existing custom flows.

If you require additional tools, you can either:
* Install them during runtime, or
* Extend the base image in advance.

👉 For detailed instructions, please see our [documentation](https://docs.env0.com/docs/extending-deployment-image).

ℹ️ Tool Download Sources
Tools are downloaded from a few external sources. If your agent is restricted by a firewall, please ensure the following domains are accessible:

* **github.com**
* **amazonaws.com**
* **dl.google.com**
* **get.helm.sh**
* **dl.k8s.io**
* **releases.hashicorp.com**
&nbsp;
## v4.0.3


- Feat: Add OnRepositoryAnalysisComplete message handler + queue @liranfarage89 (#19710)
- eng-439: pull not_started tasks + create context url @HeverFarber (#19684)&nbsp;
## v4.0.7


- Chore - dynamic placeholder priority class naming to prevent clash @chpl (#19810)
- Chore -  use cluster over provisioning instead of worm pods @chpl (#19786)
- Chore: agent level throttling - agent trigger @chpl (#19725)&nbsp;
## v4.0.7


- Chore - dynamic placeholder priority class naming to prevent clash @chpl (#19810)
- Chore -  use cluster over provisioning instead of worm pods @chpl (#19786)
- Chore: agent level throttling - agent trigger @chpl (#19725)&nbsp;
## v4.0.8


- Disable PITR in secondary regions for deployment logs DDB tables @chpl (#19816)&nbsp;
## v4.0.9


- Chore: disable-logs-for-money-saving @HeverFarber (#19813)&nbsp;
## v4.0.9


- Chore: disable-logs-for-money-saving @HeverFarber (#19813)&nbsp;
## v4.0.9


- Chore: disable-logs-for-money-saving @HeverFarber (#19813)&nbsp;
## v4.0.12


- Chore - create priority class only if agent throttling is enabled @chpl (#19857)