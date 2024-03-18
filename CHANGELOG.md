
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
## v3.0.703


- Fix: Add kubernetes path to login @liranfarage89 (#15150)