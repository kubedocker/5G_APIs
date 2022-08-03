# OpenAPI Specification Files for 3GPP 5G Core Network (Release 15)
 
© 2022, 3GPP Organizational Partners (ARIB, ATIS, CCSA, ETSI, TSDSI, TTA, TTC). All rights reserved.

API version: **June 2022**  
Release status: **{- Frozen -}**  
Other releases: [Rel-18 (Open)](https://forge.3gpp.org/rep/all/5G_APIs/tree/REL-18), [Rel-17 (Frozen)](https://forge.3gpp.org/rep/all/5G_APIs/tree/REL-17), [Rel-16 (Frozen)](https://forge.3gpp.org/rep/all/5G_APIs/tree/REL-16)

OpenAPI validation status:
[![pipeline status](https://forge.3gpp.org/rep/all/5G_APIs/badges/REL-15/pipeline.svg)](https://forge.3gpp.org/rep/all/5G_APIs/commits/REL-15)

#### Tools
* <a href="https://forge.3gpp.org/swagger/tools/parser.html" target="_blank">API Parser/Linter</a> to parse OpenAPI files with APIDevTools Swagger Parser/Validator and run a number of <a href="https://en.wikipedia.org/wiki/Lint_(software)" target="_blank">lint</a> rules to improve API quality
* <a href="https://forge.3gpp.org/swagger/tools/types.html" target="_blank">Data Type Finder</a> to find the impacted APIs due to a change on a given data type
* <a href="https://forge.3gpp.org/swagger/tools/versions.html" target="_blank">API Versions Overview</a> to show a comprehensive report of the versions of all APIs in the repository

The links below will open the Swagger Editor/UI and auto-load the OpenAPI YAML file of each Network Function (NF) API:

<!-- APIs -->
<!-- SWAGGER_EDITOR_VERSION = 3.18.0 -->

## NRF (NF Repository Function)
* NF Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_NFManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_NFManagement.yaml))
* NF Discovery
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_NFDiscovery.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_NFDiscovery.yaml))
* Oauth2 Access Token Request
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29510_Nnrf_AccessToken.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29510_Nnrf_AccessToken.yaml))

## LMF (Location Management Function)
* Location
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29572_Nlmf_Location.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29572_Nlmf_Location.yaml))

## AMF (Access and Mobility Management Function)
* Communication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_Communication.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_Communication.yaml))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_EventExposure.yaml))
* Location
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_Location.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_Location.yaml))
* MT
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29518_Namf_MT.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29518_Namf_MT.yaml))

## SMF (Session Management Function)
* PDU Session
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29502_Nsmf_PDUSession.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29502_Nsmf_PDUSession.yaml))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29508_Nsmf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29508_Nsmf_EventExposure.yaml))

## UDM (Unified Data Management)
* Subscriber Data Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_SDM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_SDM.yaml))
* UE Context Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_UECM.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_UECM.yaml))
* UE Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_UEAU.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_UEAU.yaml))
* Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_EE.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_EE.yaml))
* Parameter Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29503_Nudm_PP.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29503_Nudm_PP.yaml))

## UDR (Unified Data Repository)
* Data Repository
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29504_Nudr_DR.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29504_Nudr_DR.yaml))
  * Subscription Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29505_Subscription_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29505_Subscription_Data.yaml))
  * Policy Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29519_Policy_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Policy_Data.yaml))
  * Exposure Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29519_Exposure_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Exposure_Data.yaml))
  * Application Data
    ([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29519_Application_Data.yaml))
    ([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29519_Application_Data.yaml))

## AUSF (Authentication Server Function)
* UE Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29509_Nausf_UEAuthentication.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_UEAuthentication.yaml))
* SoR (Steering of Roaming) Protection
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29509_Nausf_SoRProtection.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_SoRProtection.yaml))
* UPU (UE Parameter Update) Protection
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29509_Nausf_UPUProtection.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29509_Nausf_UPUProtection.yaml))

## NSSF (Network Slice Selection Function)
* NSSAI Availability
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29531_Nnssf_NSSAIAvailability.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29531_Nnssf_NSSAIAvailability.yaml))
* NS Selection
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29531_Nnssf_NSSelection.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29531_Nnssf_NSSelection.yaml))

## SMSF (SMS Function)
* SM Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29540_Nsmsf_SMService.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29540_Nsmsf_SMService.yaml))

## 5G-EIR (5G Equipment Identity Register)
* Equipment Identity Check
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29511_N5g-eir_EquipmentIdentityCheck.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29511_N5g-eir_EquipmentIdentityCheck.yaml))

## NEF (Network Exposure Function)
* Packet Flow Description (PFD) Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29551_Nnef_PFDmanagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29551_Nnef_PFDmanagement.yaml))

## PCF (Policy Control Function)
* Policy Authorization
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29514_Npcf_PolicyAuthorization.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29514_Npcf_PolicyAuthorization.yaml))
* Access and Mobility (AM) Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29507_Npcf_AMPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29507_Npcf_AMPolicyControl.yaml))
* Session Management (SM) Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29512_Npcf_SMPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29512_Npcf_SMPolicyControl.yaml))
* Background Data Transfer (BDT) Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29554_Npcf_BDTPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29554_Npcf_BDTPolicyControl.yaml))
* Policy Control Event Exposure
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29523_Npcf_EventExposure.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29523_Npcf_EventExposure.yaml))
* UE Policy Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29525_Npcf_UEPolicyControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29525_Npcf_UEPolicyControl.yaml))

## BSF (Binding Support Function)
* Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29521_Nbsf_Management.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29521_Nbsf_Management.yaml))

## NWDAF (Network Data Analytics Function)
* Events Subscription
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_EventsSubscription.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_EventsSubscription.yaml))
* Analytics Info
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29520_Nnwdaf_AnalyticsInfo.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29520_Nnwdaf_AnalyticsInfo.yaml))

## CHF (Charging Function)
* Spending Limit Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29594_Nchf_SpendingLimitControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29594_Nchf_SpendingLimitControl.yaml))
* Converged Charging
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS32291_Nchf_ConvergedCharging.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS32291_Nchf_ConvergedCharging.yaml))

## Common Data Types
* Common Data
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29571_CommonData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29571_CommonData.yaml))

## SEPP N32 APIs
* Handshake (N32-c)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29573_N32_Handshake.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29573_N32_Handshake.yaml))
* Forwarding (N32-f)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29573_JOSEProtectedMessageForwarding.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29573_JOSEProtectedMessageForwarding.yaml))

# Northbound and Application Layer APIs
## CAPIF (Common API Framework)
* Discover Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Discover_Service_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Discover_Service_API.yaml))
* Publish Service
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Publish_Service_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Publish_Service_API.yaml))
* Events
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Events_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Events_API.yaml))
* API Invoker Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_API_Invoker_Management_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_API_Invoker_Management_API.yaml))
* Security
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Security_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Security_API.yaml))
* Access Control Policy
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Access_Control_Policy_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Access_Control_Policy_API.yaml))
* Logging API Invocation
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Logging_API_Invocation_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Logging_API_Invocation_API.yaml))
* Auditing
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_CAPIF_Auditing_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_CAPIF_Auditing_API.yaml))
* AEF Authentication
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29222_AEF_Security_API.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29222_AEF_Security_API.yaml))

## SCEF (Service Capability Exposure Function)
>**Note:**
These APIs are not part of the 5G Core Network; these APIs are exposed by the 4G SCEF to the SCS/AS
* Event Monitoring
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_MonitoringEvent.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_MonitoringEvent.yaml))
* Resource Management of Background Data Transfer (BDT)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ResourceManagementOfBdt.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ResourceManagementOfBdt.yaml))
* Chargeable Party
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ChargeableParty.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ChargeableParty.yaml))
* Non-IP Data Delivery (NIDD)
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_NIDD.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_NIDD.yaml))
* Device Triggering
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_DeviceTriggering.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_DeviceTriggering.yaml))
* Group Message Delivery via MBMS by MB2
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_GMDviaMBMSbyMB2.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_GMDviaMBMSbyMB2.yaml))
* Group Message Delivery via MBMS by xMB
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_GMDviaMBMSbyxMB.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_GMDviaMBMSbyxMB.yaml))
* Network Status Reporting
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ReportingNetworkStatus.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ReportingNetworkStatus.yaml))
* Communication Patterns (CP) Parameters Provisioning
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_CpProvisioning.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_CpProvisioning.yaml))
* Packet Flow Description (PFD) Management
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_PfdManagement.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_PfdManagement.yaml))
* Enhanced Coverage Restriction Control
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_ECRControl.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_ECRControl.yaml))
* Network Parameter Configuration
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_NpConfiguration.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_NpConfiguration.yaml))
* Application Server (AS) Session with QoS
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_AsSessionWithQoS.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_AsSessionWithQoS.yaml))
* MSISDN-less Mobile-Originated SMS
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_MsisdnLessMoSms.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_MsisdnLessMoSms.yaml))
* Common Data
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29122_CommonData.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29122_CommonData.yaml))

## NEF (Network Exposure Function)
* Traffic Influence
([Editor](https://forge.3gpp.org/swagger/tools/loader.html?yaml=TS29522_TrafficInfluence.yaml))
([UI](https://forge.3gpp.org/swagger/tools/loader.html?action=ui&yaml=TS29522_TrafficInfluence.yaml))
