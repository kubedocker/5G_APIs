# OpenAPI Specification Files for 3GPP 5G Core Network (Release 16)

(c) 2020, 3GPP Organizational Partners (ARIB, ATIS, CCSA, ETSI, TSDSI, TTA, TTC). All rights reserved.

API version: **March 2020**
Release status: **{+ Open +}**  
Other releases: [Rel-15 (Frozen)](https://forge.etsi.org/gitlab/3GPP/5G_APIs/tree/REL-15)


OpenAPI validation status:
[![pipeline status](https://forge.etsi.org/gitlab/3GPP/5G_APIs/badges/master/pipeline.svg)](https://forge.etsi.org/gitlab/3GPP/5G_APIs/commits/master)

#### Tools
* <a href="https://forge.etsi.org/swagger/tools/GitlabOpenAPIFrontend.htm" target="_blank">Frontend</a> to invoke the Swagger Editor, Swagger UI, or to parse OpenAPI files with APIDevTools Swagger Parser/Validator, or to search for APIs referencing a data structure
* <a href="https://forge.etsi.org/swagger/tools/parser.html" target="_blank">API Parser/Linter</a> to parse OpenAPI files with APIDevTools Swagger Parser/Validator and run a number of <a href="https://en.wikipedia.org/wiki/Lint_(software)" target="_blank">lint</a> rules to improve API quality
* <a href="https://forge.etsi.org/swagger/tools/types.html" target="_blank">Data Type Finder</a> to find the impacted APIs due to a change on a given data type
* <a href="https://forge.etsi.org/swagger/tools/versions.html" target="_blank">API Versions Overview</a> to show a comprehensive report of the versions of all APIs in the repository

The links below will open the Swagger Editor/UI and auto-load the OpenAPI YAML file of each Network Function (NF) API:

<!-- APIs -->
## NRF (NF Repository Function)
* NF Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_NFManagement.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_NFManagement.yaml))
* NF Discovery
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_NFDiscovery.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_NFDiscovery.yaml))
* Oauth2 Access Token Request
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_AccessToken.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_AccessToken.yaml))
* Bootstrapping
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_Bootstrapping.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_Bootstrapping.yaml))

## LMF (Location Management Function)
* Location
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29572_Nlmf_Location.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29572_Nlmf_Location.yaml))
* Broadcast
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29572_Nlmf_Broadcast.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29572_Nlmf_Broadcast.yaml))

## AMF (Access and Mobility Management Function)
* Communication
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29518_Namf_Communication.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_Communication.yaml))
* Event Exposure
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29518_Namf_EventExposure.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_EventExposure.yaml))
* Location
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29518_Namf_Location.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_Location.yaml))
* MT (Mobile-Terminated)
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29518_Namf_MT.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_MT.yaml))

## SMF (Session Management Function)
* PDU Session
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29502_Nsmf_PDUSession.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29502_Nsmf_PDUSession.yaml))
* Event Exposure
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29508_Nsmf_EventExposure.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29508_Nsmf_EventExposure.yaml))
* NIDD (Non-IP Data Delivery)
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29542_Nsmf_NIDD.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29542_Nsmf_NIDD.yaml))

## UDM (Unified Data Management)
* Subscriber Data Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29503_Nudm_SDM.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_SDM.yaml))
* UE Context Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29503_Nudm_UECM.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_UECM.yaml))
* UE Authentication
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29503_Nudm_UEAU.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_UEAU.yaml))
* Event Exposure
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29503_Nudm_EE.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_EE.yaml))
* Parameter Provisioning
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29503_Nudm_PP.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_PP.yaml))
* NIDD (Non-IP Data Delivery) Authorization
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29503_Nudm_NIDDAU.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_NIDDAU.yaml))
* MT (Mobile-Terminated)
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29503_Nudm_MT.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_MT.yaml))

## UDR (Unified Data Repository)
* Data Repository
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29504_Nudr_DataRepository.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29504_Nudr_DataRepository.yaml))
  * Subscription Data
    ([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29505_Subscription_Data.yaml))
    ([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29505_Subscription_Data.yaml))
  * Policy Data
    ([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29519_Policy_Data.yaml))
    ([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Policy_Data.yaml))
  * Exposure Data
    ([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29519_Exposure_Data.yaml))
    ([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Exposure_Data.yaml))
  * Application Data
    ([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29519_Application_Data.yaml))
    ([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Application_Data.yaml))
* Group ID Map
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29504_Nudr_GroupIDmap.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29504_Nudr_GroupIDmap.yaml))

## UDSF (Unstructured Data Storage Function)
* Data Repository
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29598_Nudsf_DataRepository.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29598_Nudsf_DataRepository.yaml))

## AUSF (Authentication Server Function)
* UE Authentication
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29509_Nausf_UEAuthentication.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_UEAuthentication.yaml))
* SoR (Steering of Roaming) Protection
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29509_Nausf_SoRProtection.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_SoRProtection.yaml))
* UPU (UE Parameter Update) Protection
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29509_Nausf_UPUProtection.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_UPUProtection.yaml))

## NSSF (Network Slice Selection Function)
* NSSAI Availability
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29531_Nnssf_NSSAIAvailability.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29531_Nnssf_NSSAIAvailability.yaml))
* NS Selection
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29531_Nnssf_NSSelection.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29531_Nnssf_NSSelection.yaml))

## SMSF (SMS Function)
* SM Service
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29540_Nsmsf_SMService.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29540_Nsmsf_SMService.yaml))

## 5G-EIR (5G Equipment Identity Register)
* Equipment Identity Check
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29511_N5g-eir_EquipmentIdentityCheck.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29511_N5g-eir_EquipmentIdentityCheck.yaml))

## NEF (Network Exposure Function)
* Packet Flow Description (PFD) Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29551_Nnef_PFDmanagement.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29551_Nnef_PFDmanagement.yaml))
* Session Management (SM) Context
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29541_Nnef_SMContext.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29541_Nnef_SMContext.yaml))
* NEF Event Exposure
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29591_Nnef_EventExposure.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29591_Nnef_EventExposure.yaml))

## PCF (Policy Control Function)
* Policy Authorization
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29514_Npcf_PolicyAuthorization.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29514_Npcf_PolicyAuthorization.yaml))
* Access and Mobility (AM) Policy Control
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29507_Npcf_AMPolicyControl.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29507_Npcf_AMPolicyControl.yaml))
* Session Management (SM) Policy Control
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29512_Npcf_SMPolicyControl.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29512_Npcf_SMPolicyControl.yaml))
* Background Data Transfer (BDT) Policy Control
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29554_Npcf_BDTPolicyControl.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29554_Npcf_BDTPolicyControl.yaml))
* Policy Control Event Exposure
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29523_Npcf_EventExposure.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29523_Npcf_EventExposure.yaml))
* UE Policy Control
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29525_Npcf_UEPolicyControl.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29525_Npcf_UEPolicyControl.yaml))

## BSF (Binding Support Function)
* Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29521_Nbsf_Management.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29521_Nbsf_Management.yaml))

## NWDAF (Network Data Analytics Function)
* Events Subscription
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_EventsSubscription.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_EventsSubscription.yaml))
* Analytics Info
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_AnalyticsInfo.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_AnalyticsInfo.yaml))

## HSS (Home Subscriber Server)
* UE Authentication
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29563_Nhss_UEAU.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29563_Nhss_UEAU.yaml))
* Subscriber Data Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29563_Nhss_SDM.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29563_Nhss_SDM.yaml))
* UE Context Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29563_Nhss_UECM.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29563_Nhss_UECM.yaml))
* IMS UE Authentication
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29562_Nhss_imsUEAU.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_UEAU.yaml))
* IMS Subscriber Data Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29562_Nhss_imsSDM.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_SDM.yaml))
* IMS UE Context Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29562_Nhss_imsUECM.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29562_Nhss_UECM.yaml))

## SOR-AF (Steering of Roaming Application Function)
* Steering of Roaming
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29550_Nsoraf_SOR.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29550_Nsoraf_SOR.yaml))

## SP-AF (Secured Packed Application Function)
* Secured Packet
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29544_Nspaf_SecuredPacket.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29544_Nspaf_SecuredPacket.yaml))

## AF (Application Function)
* Event Exposure
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29517_Naf_EventExposure.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29517_Naf_EventExposure.yaml))

## CHF (Charging Function)
* Spending Limit Control
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29594_Nchf_SpendingLimitControl.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29594_Nchf_SpendingLimitControl.yaml))
* Converged Charging
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS32291_Nchf_ConvergedCharging.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS32291_Nchf_ConvergedCharging.yaml))
* Offline-Only Charging
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS32291_Nchf_OfflineOnlyCharging.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS32291_Nchf_OfflineOnlyCharging.yaml))

## Common Data Types
* Common Data
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29571_CommonData.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29571_CommonData.yaml))

## SEPP N32 APIs
* Handshake (N32-c)
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29573_N32_Handshake.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29573_N32_Handshake.yaml))
* Forwarding (N32-f)
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29573_JOSEProtectedMessageForwarding.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29573_JOSEProtectedMessageForwarding.yaml))
* Telescopic FQDN Mapping
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29573_SeppTelescopicFqdnMapping.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29573_SeppTelescopicFqdnMapping.yaml))

## UCMF (UE Radio Capability Management Function)
* UE Radio Capability Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29673_Nucmf_UERCM.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29673_Nucmf_UERCM.yaml))
* Provisioning
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29675_Nucmf_Provisioning.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29675_Nucmf_Provisioning.yaml))

## GMLC (Gateway Mobile Location Center)
* Location
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29515_Ngmlc_Location.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29515_Ngmlc_Location.yaml))

# Northbound APIs (CAPIF)
* Discover Service
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Discover_Service_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Discover_Service_API.yaml))
* Publish Service
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Publish_Service_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Publish_Service_API.yaml))
* Events
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Events_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Events_API.yaml))
* API Invoker Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_API_Invoker_Management_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_API_Invoker_Management_API.yaml))
* Security
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Security_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Security_API.yaml))
* Access Control Policy
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Access_Control_Policy_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Access_Control_Policy_API.yaml))
* Logging API Invocation
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Logging_API_Invocation_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Logging_API_Invocation_API.yaml))
* Auditing
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Auditing_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Auditing_API.yaml))
* AEF Authentication
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_AEF_Security_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_AEF_Security_API.yaml))
* API Provider Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_API_Provider_Management_API.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_API_Provider_Management_API.yaml))

# Northbound APIs
## NEF (Network Exposure Function)
* Traffic Influence
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_TrafficInfluence.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_TrafficInfluence.yaml))
* NIDD (Non-IP Data Delivery) Configuration Trigger
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_NIDDConfigurationTrigger.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_NIDDConfigurationTrigger.yaml))
* 5G LAN Parameter Provision
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_5GLANParameterProvision.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_5GLANParameterProvision.yaml))
* Applying BDT Policy
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_ApplyingBdtPolicy.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_ApplyingBdtPolicy.yaml))
* IPTV Configuration
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_IPTVConfiguration.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_IPTVConfiguration.yaml))
* Analytics Exposure
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_AnalyticsExposure.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_AnalyticsExposure.yaml))
* LPI (Location Privacy Indicator) Parameter Provision
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_LpiParameterProvision.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_LpiParameterProvision.yaml))
* Service Parameter
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29522_ServiceParameter.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29522_ServiceParameter.yaml))

## VAE (V2X Application Enabler)
* V2X Message Delivery
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29486_VAE_MessageDelivery.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_MessageDelivery.yaml))
* File Distribution
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29486_VAE_FileDistribution.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_FileDistribution.yaml))
* Application Requirement
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29486_VAE_ApplicationRequirement.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_ApplicationRequirement.yaml))
* Dynamic Group
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29486_VAE_DynamicGroup.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_DynamicGroup.yaml))
* Service Continuity
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29486_VAE_ServiceContinuity.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29486_VAE_ServiceContinuity.yaml))

## SEAL (Service Enabler Architecture Layer)
* Network Resource Adaptation
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29549_SS_NetworkResourceAdaptation.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_NetworkResourceAdaptation.yaml))
* User Profile Retrival
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29549_SS_UserProfileRetrieval.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_UserProfileRetrieval.yaml))
* Events
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29549_SS_Events.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_Events.yaml))
* Group Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29549_SS_GroupManagement.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29549_SS_GroupManagement.yaml))

## SCEF (Service Capability Exposure Function)
>**Note:**
These APIs are not part of the 5G Core Network; these APIs are exposed by the 4G SCEF to the SCS/AS
* Event Monitoring
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_MonitoringEvent.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_MonitoringEvent.yaml))
* Resource Management of Background Data Transfer (BDT)
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_ResourceManagementOfBdt.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ResourceManagementOfBdt.yaml))
* Chargeable Party
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_ChargeableParty.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ChargeableParty.yaml))
* Non-IP Data Delivery (NIDD)
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_NIDD.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_NIDD.yaml))
* Device Triggering
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_DeviceTriggering.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_DeviceTriggering.yaml))
* Group Message Delivery via MBMS by MB2
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_GMDviaMBMSbyMB2.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_GMDviaMBMSbyMB2.yaml))
* Group Message Delivery via MBMS by xMB
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_GMDviaMBMSbyxMB.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_GMDviaMBMSbyxMB.yaml))
* Network Status Reporting
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_ReportingNetworkStatus.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ReportingNetworkStatus.yaml))
* Communication Patterns (CP) Parameters Provisioning
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_CpProvisioning.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_CpProvisioning.yaml))
* Packet Flow Description (PFD) Management
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_PfdManagement.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_PfdManagement.yaml))
* Enhanced Coverage Restriction Control
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_ECRControl.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ECRControl.yaml))
* Network Parameter Configuration
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_NpConfiguration.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_NpConfiguration.yaml))
* Application Server (AS) Session with QoS
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_AsSessionWithQoS.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_AsSessionWithQoS.yaml))
* MSISDN-less Mobile-Originated SMS
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_MsisdnLessMoSms.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_MsisdnLessMoSms.yaml))
* RACS (Radio Capability Signaling) Parameter Provisioning
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_RacsParameterProvisioning.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_RacsParameterProvisioning.yaml))
* Common Data
([Editor](https://forge.etsi.org/swagger/tools/loader.html?yaml=TS29122_CommonData.yaml))
([UI](https://forge.etsi.org/swagger/tools/loader.html?action=ui&yaml=TS29122_CommonData.yaml))
