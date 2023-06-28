
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
- Stability Improvement