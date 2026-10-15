# Summary
<!--
SUMMARY.md: GitBook sidebar navigation. Example: - [Label](path/file.md)

[Low Risk]
- Modify []      -> Change label
- Adjust indent  -> Change hierarchy
- Line/Comment   -> Show/hide page

[High Risk]
- Modify ()      -> Risk broken link if path invalid
- Move/Rename    -> Update SUMMARY.md, MAPPING.md, images, and internal links
- Delete file    -> Deletes source content (hiding in SUMMARY only removes from nav)
- Mappings       -> Record PDF / GitBook / App changes in MAPPING.md
-->

## Begin

- [Introduction](Begin/Introduction.md)
- [Installation](Begin/Installation.md)
- [Initialization](Begin/Initialization.md)
- [Layout](Begin/Layout.md)

## Monitor

- [System Overview](Monitor/SystemOverview/SystemOverview.md)
  - [Device Information](Monitor/DeviceInfo/DeviceInfo.md)
    - [Hardware Sensor](Monitor/HWSensor/HWSensor.md)
    - [Utilization](Monitor/Utilization/Utilization.md)
    - [Inventory](Monitor/Inventory/Inventory.md)
    - [Software](Monitor/Software/Software.md)
    - [Event Log](Monitor/EventLog/EventLog.md)
    - [BMC](Monitor/BMC/BMC.md)
    - [BIOS](Monitor/BIOS/BIOS.md)
    - [Security](Monitor/Security/Security.md)
    - [Configuration](Monitor/DeviceConfig/DeviceConfig.md)
    - [GPU](Monitor/GPUInfo/GPUInfo.md)
  - [Redfish Information](Monitor/Redfish/RedfishInfo.md)
    - [Log](Monitor/Redfish/RedfishLogs.md)
- [VM Overview](Monitor/VMOverview/VMOverview.md)
  - [Host Information](Monitor/VMHostInfo/VMHostInfo.md)
    - [Hardware Sensor](Monitor/VMHostInfo/VMHostHWSensor.md)
- [Storage Overview](Monitor/StorageOverview/StorageOverview.md)
- [POD Overview](Monitor/PODMgm/PODOverview.md)
  - [POD Information](Monitor/PODMgm/PODEdit.md)
- [Service Overview](Monitor/ServiceOverview/ServiceOverview.md)
  - [Service History Overview](Monitor/ServiceOverview/ServiceAllHistory.md)
  - [Service Event Log](Monitor/ServiceOverview/ServiceEventLog.md)
  - [Service Information](Monitor/ServiceOverview/ServiceSingleHistory.md)
- [OOB Management](Monitor/OOBMgmt/OOBMgmt.md)

## Deployment

- [Agent Management](Deployment/AgentMgm/AgentMgm.md)
  - [Deploy Agents](Deployment/AgentMgm/AgentAdd.md)
  - [Deployed Agent Report](Deployment/AgentMgm/AgentAddRep.md)
  - [Scan and Deploy](Deployment/AgentMgm/AgentScanAdd.md)
  - [Remove Agents](Deployment/AgentMgm/AgentRemove.md)
  - [Removed Agents Report](Deployment/AgentMgm/AgentRemoveRep.md)
- [Agentless Management](Deployment/AgentlessMgm/AgentlessMgm.md)
  - [Add vSphere](Deployment/AgentlessMgm/AgentlessVMwareAdd.md)
  - [Remove vSphere](Deployment/AgentlessMgm/AgentlessVMwareRemove.md)
  - [Add Redfish](Deployment/AgentlessMgm/AgentlessRedfishAdd.md)
  - [Remove Redfish](Deployment/AgentlessMgm/AgentlessRedfishRemove.md)
  - [Redfish Profile](Deployment/AgentlessMgm/AgentlessRedfishProfile.md)
    - [Redfish Profile Information](Deployment/AgentlessMgm/AgentlessRedfishProfileInfo.md)
  - [Redfish Change Password](Deployment/AgentlessMgm/AgentlessRedfishPwdChange.md)
  - [Add Storage](Deployment/AgentlessMgm/AgentlessStorageAdd.md)
  - [Remove Storage](Deployment/AgentlessMgm/AgentlessStorageRemove.md)

## Centralized

- [Metadata Management](Centralized/MetadataMgm/MetadataMgm.md)
- [BIOS Flash Management](Centralized/BIOSFlashMgm/BIOSFlashMgm.md)
  - [BIOS Cache](Centralized/BIOSFlashMgm/BIOSCache.md)
  - [BIOS Flash Task](Centralized/BIOSFlashMgm/BIOSFlashTask.md)
  - [BIOS Flash Report](Centralized/BIOSFlashMgm/BIOSFlashRep.md)
- [Security Management](Centralized/SecurityMgm/SecurityMgm.md)
  - [Device Access Control](Centralized/SecurityMgm/DeviceAccessCtrl.md)
  - [Software Blocklist](Centralized/SecurityMgm/SWBlocklist.md)
    - [Software Blocklist Information](Centralized/SecurityMgm/SWBlocklistInfo.md)
  - [Policy Management](Centralized/SecurityMgm/PolicyMgm.md)
- [Software Dispatch](Centralized/SWDispMgm/SWDispMgm.md)
  - [Software Pool](Centralized/SWDispMgm/SWPool.md)
  - [Software Dispatch Task](Centralized/SWDispMgm/SWDispTask.md)
  - [Software Dispatch Report](Centralized/SWDispMgm/SWDispTaskRep.md)
- [Task Scheduler](Centralized/TaskScherMgm/TaskScherMgm.md)
  - [Taskset Editor](Centralized/TaskScherMgm/TaskSetEditor.md)
- [Power Control](Centralized/PowerControl/PowerControl.md)
- [Firmware Management](Centralized/FirmwareMgm/FirmwareMgm.md)
  - [Edit Host](Centralized/FirmwareMgm/NodeInfo.md)
  - [Firmware Information](Centralized/FirmwareMgm/FirmwareInfo.md)
  - [Firmware Update](Centralized/FirmwareMgm/FirmwareUpdate.md)
  - [Redfish Firmware Cache](Deployment/AgentlessMgm/AgentlessRedfishFWUpdateCache.md)
  - [Redfish Firmware Update](Deployment/AgentlessMgm/AgentlessRedfishFWUpdateTask.md)
  - [Firmware Update Summary](Centralized/FirmwareMgm/FWUpdateTaskRepSummary.md)
    - [Firmware Task Report](Centralized/FirmwareMgm/FWUpdateTaskRep.md)
  - [Redfish Firmware Update Report](Deployment/AgentlessMgm/AgentlessRedfishFWUpdateRep.md)
- [Service Management](Centralized/ServiceMgm/ServiceMgm.md)
  - [Edit Service](Centralized/ServiceMgm/ServiceEdit.md)
  - [Edit Host](Centralized/ServiceMgm/ServiceEditHost.md)
  - [Service History](Centralized/ServiceMgm/ServiceHistory.md)

## Report

- [Software Report](Report/SoftwareReportMgm/SoftwareReportMgm.md)
  - [Software Inventory](Report/SoftwareReportMgm/SWInventoryReport.md)
  - [Hotfix Report](Report/SoftwareReportMgm/HotfixReport.md)
  - [License Report](Report/SoftwareReportMgm/SWLicenseReport.md)
  - [Service Report](Report/SoftwareReportMgm/ServiceReport.md)
  - [Application Usage Analysis](Report/SoftwareReportMgm/AppUsageAnalysis.md)
  - [Application Change Log](Report/SoftwareReportMgm/AppChangelogReport.md)
  - [Event Log Center](Report/SoftwareReportMgm/EventLogCenter.md)
- [Hardware Report](Report/HardwareReportMgm/HardwareReportMgm.md)
  - [Hardware Inventory](Report/HardwareReportMgm/HWInventoryReport.md)
  - [Hardware Inventory Change Log](Report/HardwareReportMgm/HWChangelogReport.md)
- [Task Report](Report/TaskReport/TaskReport.md)
  - [Software Dispatch](Report/TaskReport/SWDispRepSummary.md)
  - [BIOS Flash](Report/TaskReport/BIOSFlashRepSummary.md)
  - [Agent Update](Report/TaskReport/UpdateRepSummary.md)
  - [Agent Deploy](Report/TaskReport/AgentDeployRepSummary.md)
  - [Redfish Firmware Update Report](Report/TaskReport/AgentlessRedfishFWUpdateTaskRepSummary.md)
  - [SSH Key Rotation](Report/TaskReport/SSHKeyUpdateSummary.md)
  - [SSH Key Rotation Report](Report/TaskReport/SSHKeyUpdateTaskRep.md)

## Notification

- [Conditional Trigger](Notification/ConditionalTrigger/ConditionalTrigger.md)
  - [Trust Software Asset](Notification/ConditionalTrigger/SWTrustListAssetChange.md)
  - [Focus Software Asset](Notification/ConditionalTrigger/SWFocusListAssetChange.md)
  - [Hardware Asset](Notification/ConditionalTrigger/HardwareAssetChange.md)
  - [Hardware & Utilization](Notification/ConditionalTrigger/HWUtilStatusChange.md)
- [Subscription](Notification/Subscription/Subscription.md)
  - [Subscription Report](Notification/Subscription/SWSubscriptionReport.md)
    - [Subscription Report Information](Notification/Subscription/SWSubscriptionReportInfo.md)

## Account

- [Role Privilege Management](Account/RolePrivMgm/RolePrivMgm.md)
  - [Role Configuration](Account/RolePrivMgm/RolePrivConfig.md)
- [Accounts Management](Account/AccountMgm/AccountMgm.md)
- [System Audit Log](Account/SystemAuditLog/SystemAuditLog.md)

## Options

- [Options](Options/Options/Options.md)
  - [General Configuration](Options/Options/GeneralConfig.md)
  - [Network Configuration](Options/Options/NetworkConfig.md)
  - [Appearance Configuration](Options/Options/ApperanceConfig.md)
  - [Security Configuration](Options/Options/SecurityConfig.md)
  - [SMTP Settings](Options/Options/SMTPSetting.md)
  - [Backup & Restore](Options/Options/BackupRestore.md)
  - [Maintenance](Options/Options/Maintenance.md)
  - [DBExpose Configuration](Options/Options/DBExposeConfig.md)
  - [Update](Options/Options/Update.md)
    - [Update Report](Options/Options/UpdateReport.md)
  - [Access Control List](Options/Options/ACL.md)
  - [Customize Page](Options/Options/CustomizePage.md)
    - [Customize Page Information](Options/Options/CustomizePageInfo.md)
  - [Threshold](Options/Options/SensorThresholdConfig.md)
  - [Software List](Options/Options/SWList.md)
    - [Software List Information](Options/Options/SWListInfo.md)

## License

- [License](License/License/License.md)