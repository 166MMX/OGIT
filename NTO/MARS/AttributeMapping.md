# Mapping of attributes from MARS XML Schema to ontology attributes

* old attributes starting with "/" (free attributes) were defined in [MARS XML Schema](https://github.com/arago/MARS-Schema/blob/master/schemas/MARSSchema2015.xsd)
* a few old attributes come from `ogit/Automation` NTO

|old attribute name| allowed for Node type | mandatory in MARS Schema? | new attribute name | mandatory in MARS NTO?|
| --- | --- | --- | --- | --- |
|/ApplicationClass|Application|yes|ogit/MARS/Application/class|yes|
|/ApplicationContact|Application||||
|/ApplicationSubClass|Application|yes|ogit/MARS/Application/subClass|yes|
|/AutomationState|all||ogit/Automation/automationState||
|/AvailableServices|Machine||||
|/BasePath|Software||ogit/MARS/Software/installPath||
|/CPUModel|Machine||||
|/CPUQuantity|Machine||||
|/CPUSpeed|Machine||||
|/Clustertype|all||||
|/ConfigFile|Software||||
|/CustomerID|all|yes| replaced by data ownership|no|
|/CustomerName|all||||
|/DB|Software||||
|/DataCenterCity|Machine||||
|/DataCenterCountry|Machine||||
|/DataCenterName|Machine||||
|/DataCenterRackUnit|Machine||||
|/DataCenterRack|Machine||||
|/DataCenterRoom|Machine||||
|/DataCenterStreet|Machine||||
|/DisabledServices|Machine||||
|/DockerContainerName|Software||||
|/EventCounter.Critical|all||||
|/EventCounter.Warning|all||||
|/FQDN|Machine||ogit/MARS/Network/fqdn||
|/FilesystemMountOptions|Machine||||
|/FilesystemMountPoint|Machine||||
|/FilesystemSpaceTotal|Machine||||
|/FilesystemSpaceUnit|Machine||||
|/FilesystemType|Machine||||
|/Filesystem|Machine||||
|/HWModel|Machine||||
|/HWRAM|Machine||ogit/MARS/Machine/ram||
|/HWSerialNo|Machine||ogit/serialNumber||
|/HWServiceContractContractEndDate|Machine||ogit/endOfWarranty||
|/HWServiceContractContractID|Machine||||
|/HWServiceContractContractName|Machine||||
|/HWServiceContractContractStartDate|Machine||||
|/HWServiceContractContractType|Machine||||
|/HWVendor|Machine||||
|/HardwareContact|Machine||||
|/HasAgentType_WatchMe|all||||
|/ID|all|yes|ogit/_xid|(no)|
|/Instance|Software||ogit/MARS/Software/instanceId||
|/LogAccessLogPattern|Software||||
|/LogDefaultLogPattern|Software||||
|/LogErrorLogPattern|Software||||
|/LogPath|Software||ogit/MARS/Software/logPath||
|/MachineArchitecture|Machine||ogit/MARS/Machine/cpuArch|X|
|/MachineClass|Machine|yes|ogit/MARS/Machine/class|yes|
|/ManualServices|Machine||||
|/MonitoringStatusMessage|all||||
|/MonitoringStatus|all||ogit/Automation/serviceStatus||
|/NetworkDefaultGW|Machine||ogit/MARS/Network/defaultGateway||
|/NetworkIP|Software||ogit/MARS/Network/bindAddress||
|/NetworkInterfaceIP|Machine||ogit/MARS/Network/interfaceIP||
|/NetworkInterfaceMAC|Machine||ogit/MARS/Network/interfaceMAC||
|/NetworkInterfaceNetmask|Machine||ogit/MARS/Network/interfacePrefixLength||
|/NetworkInterfacePrefixLength|Machine||ogit/MARS/Network/interfacePrefixLength||
|/NetworkInterfaceType|Machine||ogit/MARS/Network/ipVersion||
|/NetworkInterface|Machine||ogit/MARS/Network/interfaceName||
|/NetworkPort|Software||ogit/MARS/Network/port||
|/NetworkProtocol|Software||ogit/MARS/Network/protocol||
|/NodeID|all|(yes)|ogit/_xid|(no)|
|/NodeName|all|yes|ogit/name|yes|
|/NodeType|all|yes|ogit/_type|(yes)|
|/NominalState|all||||
|/OSKernel|Machine||ogit/MARS/Machine/kernel||
|/OSLang|Machine||||
|/OSLicense|Machine||||
|/OSMajorVersion|Machine||ogit/Version/major||
|/OSMinorVersion|Machine||ogit/Version/minor||
|/OSName|Machine||ogit/MARS/Machine/distroName||
|/OSPatchLevel|Machine||ogit/Version/patch||
|/OSVendor|Machine||ogit/vendor||
|/Password|Software||||
|/ProcessName|Software||||
|/ProcessUser|Software||||
|/ResourceClass|Resource|yes|ogit/MARS/Resource/class|yes|
|/ResourceContact|Resource||||
|/RouteDestination|Machine||||
|/RouteGateway|Machine||||
|/RouteInterface|Machine||||
|/RouteNetmask|Machine||||
|/Route|Machine||||
|/RunningServices|Machine||||
|/SLA|all||||
|/SWLicense|Software||||
|/SWMajorVersion|Software||ogit/Version/major||
|/SWMinorVersion|Software||ogit/Version/minor||
|/SWName|Software||||
|/SWPatchLevel|Software||ogit/Version/patch||
|/SWServiceContractContractEndDate|Software||ogit/endOfWarranty||
|/SWServiceContractContractID|Software||||
|/SWServiceContractContractName|Software||||
|/SWServiceContractContractStartDate|Software||||
|/SWServiceContractContractType|Software||||
|/SWVendor|Software||ogit/vendor||
|/ServiceContact|all||||
|/ServiceName|Software||ogit/MARS/Software/serviceName||
|/SoftwareClass|Software|yes|ogit/MARS/Software/class|yes|
|/SoftwareContact|Software||||
|/SoftwareSubClass|Software|yes|ogit/MARS/Software/subClass|yes|
|/StartScript|Software||||
|/StopScript|Software||||
|/TechContact|all||||
|/User|Software||||
|/WebServerAccessLog|Software||||
|/WebServerHosts|Software||||
|SWInstallPath|Software||ogit/MARS/Software/installPath||
|ogit/Automation/marsNodeType|all||ogit/_type|(yes)|