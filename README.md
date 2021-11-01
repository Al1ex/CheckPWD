### 项目背景

在渗透测试过程中我们经常会碰到各种应用软件与网络设备，这一点在内网中尤为凸显，而碰到类似的目标时我们的第一反应莫过于尝试默认口令登录，本项目将基于此背景对现有网络上已公开的设备口令账号进行收录，以供安全测试人员进行测试以及第三方安全厂商自检

### 口令速查

##### 硬件产品

###### 密码机

| 厂商                         | 产品                              | 口令           |
| ---------------------------- | --------------------------------- | -------------- |
| 北京三未信安科技发展有限公司 | 三未信安服务器密码机（SJJ1012-A） | swhsm/swxa1234 |

###### 路由器
|                           |                                      |                    |                                                              |
| ------------------------ | ------------------------------------- | ------------------ | ------------------------------------------------------------ |
| 厂商                      | 产品                                  | 协议                | 口令                                                         |
| 2WIRE                    | HOMEPORTAL Rev. SBC YAHOO! DSL        | (none)             | 2Wire/null                                                   |
| 2WIRE                    | ALL WIFI ROUTERS                      | HTTP               | null/Wireless                                                |
| 360 Systems              | Image Server 2000                     | HTTP               | factory/factory                                              |
| 3COM                     | COREBUILDER Rev. 7000/6000/3500/2500  | TELNET             | debug/synnet                                                 |
| 3COM                     | COREBUILDER Rev. 7000/6000/3500/2500  | TELNET             | tech/tech                                                    |
| 3COM                     | HIPERARC Rev. V4.1.X                  | TELNET             | adm/(none)                                                   |
| 3COM                     | LANPLEX Rev. 2500                     | TELNET             | debug/synnet                                                 |
| 3COM                     | LANPLEX Rev. 2500                     | TELNET             | tech/tech                                                    |
| 3COM                     | LINKSWITCH Rev. 2000/2700             | TELNET             | tech/tech                                                    |
| 3COM                     | NETBUILDER                            | SNMP               | (none)/ANYCOM                                                |
| 3COM                     | NETBUILDER                            | SNMP               | (none)/ILMI                                                  |
| 3COM                     | NETBUILDER                            | MULTI              | admin/(none)                                                 |
| 3COM                     | OFFICE CONNECT ISDN ROUTERS Rev. 5X0  | TELNET             | n/a/PASSWORD                                                 |
| 3COM                     | SUPERSTACK II SWITCH Rev. 2200        | TELNET             | debug/synnet                                                 |
| 3COM                     | SUPERSTACK II SWITCH Rev. 2700        | TELNET             | tech/tech                                                    |
| 3COM                     | 812 ADSL                              | MULTI              | adminttd/adminttd                                            |
| 3COM                     | WIRELESS AP Rev. ANY                  | MULTI              | admin/comcomcom                                              |
| 3COM                     | CELLPLEX Rev. 7000                    | TELNET             | tech/tech                                                    |
| 3COM                     | CELLPLEX Rev. 7000                    | TELNET             | admin/admin                                                  |
| 3COM                     | LANPLEX Rev. 2500                     | TELNET             | tech/(none)                                                  |
| 3COM                     | CELLPLEX                              | HTTP               | admin/synnet                                                 |
| 3COM                     | CELLPLEX Rev. 7000                    | TELNET             | root/(none)                                                  |
| 3COM                     | HIPERACT Rev. V4.1.X                  | TELNET             | admin/(none)                                                 |
| 3COM                     | CELLPLEX Rev. 7000                    | TELNET             | tech/(none)                                                  |
| 3COM                     | SUPERSTACK 3 Rev. 4XXX                | MULTI              | admin/(none)                                                 |
| 3COM                     | SUPERSTACK 3 Rev. 4XXX                | MULTI              | monitor/monitor                                              |
| 3COM                     | SUPERSTACK 3 Rev. 4400-49XX           | MULTI              | manager/manager                                              |
| 3COM                     | NETBUILDER                            | HTTP               | Root/(none)                                                  |
| 3COM                     | 3C16450                               | MULTI              | admin/(none)                                                 |
| 3COM                     | 3C16406                               | MULTI              | admin/(none)                                                 |
| 3COM                     | OFFICE CONNECT ISDN ROUTERS Rev. 5X0  | TELNET             | n/a/PASSWORD                                                 |
| 3COM                     | COREBUILDER Rev. 7000/6000/3500/2500  | TELNET             | n/a/admin                                                    |
| 3COM                     | COREBUILDER Rev. 7000/6000/3500/2500  | TELNET             | n/a/(none)                                                   |
| 3COM                     | ADSL WIRELESS 11G                     | HTTP               | (none)/admin                                                 |
| 3COM                     | INTERNET FIREWALL Rev. 3C16770        | HTTP               | admin/password                                               |
| 3COM                     | SHARK FIN Rev. COMCAST-SUPPLIED       | HTTP               | User/Password                                                |
| 3COM                     | 812                                   | HTTP               | Administrator/admin                                          |
| 3COM                     | CELLPLEX Rev. 7000                    | TELNET             | operator/(none)                                              |
| 3COM                     | 3COM SUPERSTACK 3 SWITCH 3300XM       | MULTI              | security/security                                            |
| 3COM                     | SUPERSTACK II Rev. 1100/3300          | CONSOLE            | 3comcso/RIP000                                               |
| 3COM                     | NETBUILDER                            | SNMP               | (none)/admin                                                 |
| 3COM                     | SUPER                                 | TELNET             | admin/(none)                                                 |
| 3COM                     | CELLPLEX Rev. 7000                    | MULTI              | admin/admin                                                  |
| 3COM                     | 812 ADSL Rev. 01.50-01                | MULTI              | admin/(none)                                                 |
| 3COM                     | CELLPLEX                              | MULTI              | admin/admin                                                  |
| 3COM                     | 3C16405                               | CONSOLE            | Administrator/(none)                                         |
| 3COM                     | SWITCH Rev. 3300XM                    | MULTI              | admin/admin                                                  |
| 3COM                     | SS III SWITCH Rev. 4XXX (4900 - SURE) | TELNET             | recovery/recovery                                            |
| 3COM                     | WIRELESS 11G CABLE/DSL GATEWAY        | HTTP               | (none)/admin                                                 |
| 3COM                     | 3C16405                               | MULTI              | admin/(none)                                                 |
| 3COM                     | 3CRADSL72 Rev. 1.2                    | MULTI              | (none)/1234admin                                             |
| 3COM                     | CB9000 / 4007 Rev. 3                  | CONSOLE            | Type User: FORCE/(none)                                      |             
| 3COM                     | OFFICE CONNECT Rev. 11G               | MULTI              | admin/(none)                                                 |
| 3com                     | 3comCellPlex7000                      |                    | tech/tech                                                    |
| 3COM                     | AccessBuilder                         | SNMP               | SNMPWrite/private                                            |
| 3COM                     | AirConnect Access                     | Multi              | (none)/(none)                                                |
| 3Com                     | AirConnect Access Point               |                    | (none)/comcomcom                                             |
| 3com                     | Cable Managment                       |                    | DOCSIS_APP/3com                                              |
| 3COM                     | CellPlex                              | Telnet             | admin/(none)                                                 |
| 3COM                     | CellPlex                              | Telnet             | (none)/(none)                                                |
| 3COM                     | CellPlex                              | Telnet             | root/(none)                                                  |
| 3COM                     | CellPlex                              | Telnet             | tech/(none)                                                  |
| 3COM                     | CoreBuilder                           | Telnet             | operator/admin                                               |
| 3COM                     | CoreBuilder                           | SNMP               | SNMPWrite/private                                            |
| 3Com                     | CoreBuilder                           |                    | debug/tech                                                   |
| 3COM                     | HiPerARC                              | Telnet             | adm/(none)                                                   |
| 3com                     | Home Connect                          |                    | User/Password                                                |
| 3COM                     | LANplex                               | Telnet             | tech/tech                                                    |
| 3COM                     | LinkBuilder                           | Telnet             | tech/tech                                                    |
| 3COM                     | LinkSwitch                            | Telnet             | tech/tech                                                    |
| 3Com                     | LinkSwitch and CellPlex               |                    | tech/tech                                                    |
| 3com                     | NBX100                                |                    | administrator/0                                              |
| 3COM                     | NetBuilder                            | Multi              | admin/(none)                                                 |
| 3COM                     | NetBuilder                            | SNMP               | (none)/ILMI                                                  |
| 3COM                     | NetBuilder                            | SNMP               | (none)/ANYCOM                                                |
| 3COM                     | OCR-812                               |                    | root/!root                                                   |
| 3COM                     | Office Connect                        | Multi              | root/!root                                                   |
| 3COM                     | Office Connect                        | Telnet             | (none)/PASSWORD                                              |
| 3Com                     | 5×1                                   |                    | (none)/PASSWORD                                              |
| 3com                     | 812 ADSL                              | Multi              | adminttd/adminttd                                            |
| 3Com                     | SuperStack / CoreBuilder              |                    | admin/(none)                                                 |
| 3Com                     | SuperStack / CoreBuilder              |                    | write/(none)                                                 |
| 3com                     | Superstack II 3300FX                  |                    | admin/(none)                                                 |
| 3COM                     | SuperStack II Switch                  | Console            | 3comcso/RIP000                                               |
| 3COM                     | SuperStack II Switch                  | Telnet             | debug/synnet                                                 |
| 3COM                     | SuperStack II Switch                  | Telnet             | monitor/monitor                                              |
| 3COM                     | SuperStack II Switch                  | Telnet             | security/security                                            |
| 3Com                     | SuperStack II Switch 1100             |                    | manager/manager                                              |
| 3Com                     | SuperStack II Switch 2200             |                    | debug/synnet                                                 |
| 3Com                     | SuperStack II Switch 3300             |                    | manager/manager                                              |
| 3COM                     | SuperStack III Switch                 | Multi              | manager/manager                                              |
| 3COM                     | SuperStack III Switch                 | Multi              | recovery/recovery                                            |
| 3COM                     | Switch                                | Multi              | admin/admin                                                  |
| 3com                     | Switch 3000/3300                      |                    | Admin/3com                                                   |
| 3Com                     | Switch 3000/3300                      |                    | monitor/monitor                                              |
| 3COM                     | Wireless AP                           | Multi              | admin/comcomcom                                              |
| 3COM                     |                                       | Telnet             | admin/synnet                                                 |
| 3COM                     |                                       | Telnet             | monitor/monitor                                              |
| 3COM                     |                                       | Telnet             | security/security                                            |
| 3COM                     |                                      |                    | root/letmein                                                 |
| 3M                       | Volition Fibre Switches               | SNMP               | volition/volition                                            |
| 3M                       | VOL-0215                              | SNMP               | volition/(none)                                              |
| 3M                       | VOL-0215                              | HTTP               | VOL-0215/(none)                                              |
| 3WARE                    | 3WARE                                 | HTTP               | Administrator/3ware                                          |
| ACC                      | Congo/Amazon/Tigris                   | Multi              | netman/netman                                                |
| Acc-Newbridge            | Congo/Amazon/Tigris                   |                    | netman/netman                                                |
| ACCELERATED NETWORKS     | DSL CPE AND DSLAM                     | Telnet             | sysadm/anicust                                               |
| ACCONET                  | ROUTER                                | HTTP               | Admin/admin                                                  |
| ACCTON T-ONLINE          | ACCTON                                | Multi              | (none)/0                                                     |
| ACCTON T-ONLINE          | ACCTON                                | Multi              | (none)/0                                                     |
| ACEEX                    | MODEM ADSL ROUTER                     | HTTP               | admin/(none)                                                 |
| ACEEX                    | MODEM ADSL ROUTER                     | HTTP               | admin/(none)                                                 |
| Acer                     | 517te                                 | Multi              | (none)/(none)                                                |
| Acer                     | Phoenix                               | n/a                | (none)/Admin                                                 |
| Actiontec                | GE344000-01                           |                    | (none)/(none)                                                |
| Actiontec                | M1424WR                               | HTTP               | admin/password                                               |
| ADC Kentrox              | Pacesetter Router                     | Telnet             | (none)/secret                                                |
| Adaptec                  | Storage Manager PRO                   | Multi              | Administrator/adaptec                                        |
| Adaptec                  | Storage Manager PRO                   | Multi              | Administrator/adaptec                                        |
| AdComplete.com           | Ban Man Pro                           | HTTP               | Admin1/Admin1                                                |
| AdComplete.com           | Banman Pro                            | HTTP               | Admin1/Admin1                                                |
| ADP                      | ADP Payroll HR Database               | Multi              | sysadmin/master                                              |
| Adtran                   | MX2800                                | Telnet             | (none)/adtran                                                |
| Adtran                   | TSU 600 Ethernet module               |                    | 18364/(none)                                                 |
| AddPac Technology        | AP2120                                | HTTP               | root/router                                                  |
| Adobe                    | Vignette Connector                    | HTTP               | vgnadmin/vgnadmin                                            |
| Adobe                    | CQ                                    | HTTP               | admin/admin                                                  |
| Adobe                    | CQ                                    | HTTP               | author/author                                                |
| Adobe                    | Experience Manager                    | HTTP               | admin/admin                                                  |
| Adobe                    | Experience Manager/CQ                 |                    | anonymous/anonymous                                          |
| Adobe                    | Experience Manager/CQ                 |                    | replication-receiver/replication-receiver                    |
| Adobe                    | Experience Manager/CQ                 |                    | [jdoe@geometrixx.info](mailto:jdoe@geometrixx.info)/jdoe     |
| Adobe                    | Experience Manager/CQ                 |                    | [aparker@geometrixx.info](mailto:aparker@geometrixx.info)/aparker |
| ADT                      | Safewatch Pro3000                     |                    | (none)/2580                                                  |
| Adtech                   | AX4000                                |                    | root/ax400                                                   |
| Alcatel                  | Office 4200                           | Multi              | (none)/1064                                                  |
| Alcatel                  | OmniStack/OmniSwitch                  | Telnet/            | diag/switch                                                  |
| Alcatel                  | PBX                                   | Port 2533          | at4400/at4400                                                |
| Alcatel                  | PBX                                   | Port 2533          | dhs3mt/dhs3mt                                                |
| Alcatel                  | PBX                                   | Port 2533          | halt/tlah                                                    |
| Alcatel                  | PBX                                   | Port 2533          | kermit/kermit                                                |
| Alcatel                  | PBX                                   | Port 2533          | mtcl/mtcl                                                    |
| alcatel                  | speed touch home                      |                    | (none)/(none)                                                |
| Alcatel                  | VPN Gateway                           |                    | root/permit                                                  |
| Alcatel                  | Newbridge VPN Gateway                 |                    | root/permit                                                  |
| Allied                   | CJ8MO E-U                             | Telnet             | (none)/(none)                                                |
| Allied                   | Telesyn                               | Multi              | secoff/secoff                                                |
| Allied                   | CJ8MO E-U                             | Telnet             | (none)/(none)                                                |
| Allied                   | Telesyn                               | Multi              | secoff/secoff                                                |
| ALLNET                   | ALL129DSL                             |                    | admin/admin                                                  |
| Alteon                   | ACEDirector3                          | console            | admin/(none)                                                 |
| Alteon                   | ACEswitch                             | HTTP               | admin/admin                                                  |
| Alteon                   | ACEswitch                             | HTTP               | admin/linga                                                  |
| Alteon                   | ACEswitch                             | Telnet             | admin/(none)                                                 |
| Alteon                   | Web Systems                           | Telnet             | (none)/14admin                                               |
| Alteon                   | ACEDirector3                          | console            | admin/(none)                                                 |
| Alteon                   | ACEswitch                             | HTTP               | admin/admin                                                  |
| Alteon                   | ACEswitch                             | HTTP               | admin/linga                                                  |
| Alteon                   | ACEswitch                             | Telnet             | admin/(none)                                                 |
| Alteon                   | Web Systems                           | Telnet             | (none)/14admin                                               |
| AMBIT                    | ADSL                                  | Telnet             | root/(none)                                                  |
| AMI                      | AT 49                                 | Multi              | (none)/(none)                                                |
| AMI                      | PC BIOS                               | Console            | (none)/aammii                                                |
| AMI                      | PC BIOS                               | Console            | (none)/AMI.KEY                                               |
| AMI                      | PC BIOS                               | Console            | (none)/AMI~                                                  |
| AMI                      | PC BIOS                               | Console            | (none)/AMIDECOD                                              |
| AMI                      | PC BIOS                               | Console            | (none)/amipswd                                               |
| AMI                      | PC BIOS                               | Console            | (none)/BIOSPASS                                              |
| AMI                      | PC BIOS                               | Console            | (none)/AM                                                    |
| AMI                      | PC BIOS                               | Console            | (none)/A.M.I                                                 |
| AMI                      | PC BIOS                               | Console            | (none)/CMOSPWD                                               |
| Amptron                  | PC BIOS                               | Console            | (none)/Polrty                                                |
| APC                      | Any                                   |                    | apcuser/apc                                                  |
| APC                      | MasterSwitch                          |                    | apc/apc                                                      |
| APC                      | Powerchute Plus                       | Console            | POWERCHUTE/APC                                               |
| APC                      | SNMP Adapter                          |                    | apc/apc                                                      |
| APC                      | Web/SNMP                              | Multi              | apc/apc                                                      |
| Armenia                  | Forum                                 | Multi              | admin/admin                                                  |
| Arrowpoint               | any?                                  |                    | admin/system                                                 |
| Asante                   | IntraSwitch                           | Multi              | IntraSwitch/Asante                                           |
| Ascend                   | All TAOS models                       |                    | admin/Ascend                                                 |
| Ascend                   | Router                                | Telnet             | (none)/ascend                                                |
| Ascend                   | Yurie                                 | Multi              | readonly/lucenttech2                                         |
| Ascom                    | Ascotel PBX                           | Multi              | (none)/3ascotel                                              |
| Aspect                   | ACD                                   | HTTP               | customer/(none)                                              |
| Aspect                   | ACD                                   | Oracle             | DTA/TJM                                                      |
| AST                      | PC BIOS                               | Console            | (none)/SnuFG5                                                |
| Attachmate               | Attachmate Gateway                    | Console            | (none)/PASSWORD                                              |
| Audioactive              | MPEG Realtime                         | Telnet             | (none)/telos                                                 |
| Autodesk                 | Autocad                               | Multi              | autocad/autocad                                              |
| Avaya                    | Cajun                                 | Multi              | diag/danger                                                  |
| Avaya                    | Cajun                                 | Telnet             | (none)/(none)                                                |
| Avaya                    | Cajun Pxxx                            | Multi              | root/root                                                    |
| Avaya                    | Pxxx                                  | Multi              | manuf/xxyyzz                                                 |
| AWARD                    | PC BIOS                               | Console            | Administrator/admin                                          |
| AWARD                    | PC BIOS                               | Console            | (none)/256256                                                |
| AWARD                    | PC BIOS                               | Console            | (none)/(none)                                                |
| AWARD                    | PC BIOS                               | Console            | (none)/(none)                                                |
| AWARD                    | PC BIOS                               | Console            | (none)/256256                                                |
| AWARD                    | PC BIOS                               | Console            | (none)/alfarome                                              |
| AWARD                    | PC BIOS                               | Console            | (none)/aPAf                                                  |
| AWARD                    | PC BIOS                               | Console            | (none)/Award                                                 |
| AWARD                    | PC BIOS                               | Console            | (none)/AWARD_SW                                              |
| AWARD                    | PC BIOS                               | Console            | (none)/BIOS                                                  |
| AWARD                    | PC BIOS                               | Console            | (none)/biostar                                               |
| AWARD                    | PC BIOS                               | Console            | (none)/condo                                                 |
| AWARD                    | PC BIOS                               | Console            | (none)/CONDO                                                 |
| AWARD                    | PC BIOS                               | Console            | (none)/h6BB                                                  |
| AWARD                    | PC BIOS                               | Console            | (none)/HEWITT RAND                                           |
| AWARD                    | PC BIOS                               | Console            | (none)/j09F                                                  |
| AWARD                    | PC BIOS                               | Console            | (none)/j262                                                  |
| AWARD                    | PC BIOS                               | Console            | (none)/j64                                                   |
| AWARD                    | PC BIOS                               | Console            | (none)/lkwpeter                                              |
| AWARD                    | PC BIOS                               | Console            | (none)/PASSWORD                                              |
| AWARD                    | PC BIOS                               | Console            | (none)/setup                                                 |
| AWARD                    | PC BIOS                               | Console            | (none)/SW_AWARD                                              |
| AWARD                    | PC BIOS                               | Console            | (none)/Sxyz                                                  |
| AWARD                    | PC BIOS                               | Console            | (none)/t0ch20x                                               |
| AWARD                    | PC BIOS                               | Console            | (none)/TTPTHA                                                |
| AWARD                    | PC BIOS                               | Console            | (none)/wodj                                                  |
| Axent                    | NetProwler manager                    |                    | administrator/admin                                          |
| AXIS                     | 200 V1.32                             |                    | admin/(none)                                                 |
| Axis                     | NETCAM                                | Telnet             | root/pass                                                    |
| Axis                     | Printserver                           | Multi              | root/pass                                                    |
| AXIS                     | 200 V1.32                             |                    | admin/(none)                                                 |
| Axis                     | NETCAM                                | Telnet             | root/pass                                                    |
| Axis                     | Printserver                           | Multi              | root/pass                                                    |
| Axis                     | Axis                                  | HTTP               | setup/setup                                                  |
| Barco                    | Barco                                 | HTTP               | admin/admin                                                  |
| Barracuda                | SSL VPN                               | Console/HTTP       | admin/admin                                                  |
| Barracuda                | SSL VPN                               | HTTP               | ssladmin/ssladmin                                            |
| Bay Networks             | Router                                | Telnet             | Manager/(none)                                               |
| Bay Networks             | Router                                | Telnet             | User/(none)                                                  |
| Bay Networks             | SuperStack II                         | Telnet             | security/security                                            |
| Bay Networks             | Switch                                | Telnet             | (none)/NetICs                                                |
| B-FOCuS                  | B-FOCuS 270/400                       |                    | root/1234                                                    |
| Best Practical Solutions | Request Tracker                       |                    | root/password                                                |
| BestPractical            | router                                | HTTP               | root/password                                                |
| Bewan                    | Wireless Routers                      |                    | bewan/bewan                                                  |
| BEA                      | Weblogic                              |                    | system/weblogic                                              |
| BEA                      | Weblogic                              |                    | system/weblogic                                              |
| BEA                      | WebLogic Process                      |                    | joe/password                                                 |
| BEA                      | WebLogic Process                      |                    | system/security                                              |
| Beck                     | IPC@Chip                              | HTTP               | anonymous/(none)                                             |
| Beck                     | IPC@Chip                              | HTTP               | tel/(none)                                                   |
| Belkin                   | F5D6130                               | SNMP               | (none)/MiniAP                                                |
| Biscom                   | Biscom Delivery Server                | Multiple           | admin/admin                                                  |
| Billion                  | BiPAC 7404VGO                         | HTTP               | admin/admin                                                  |
| Billion                  | BiGuard                               | HTTP               | admin/admin                                                  |
| Bintec                   | all Routers                           |                    | admin/bintec or funkwerk                                     |
| Bintec                   | Bianka Routers                        | Multi              | admin/bintec                                                 |
| BioData                  | all Babylon Boxes                     |                    | (none)/Babylon                                               |
| Biostar                  | PC BIOS                               | Console            | (none)/Q54arwms                                              |
| Biostar                  | PC BIOS                               | Console            | (none)/Biostar                                               |
| BizDesign                | ImageFolio Pro                        | HTTP               | Admin/ImageFolio                                             |
| Black Duck Software      | Hub                                   | HTTP               | sysadmin/blackduck                                           |
| Black Duck Software      | Administration Console                | HTTP               | admin/admin                                                  |
| Black Widow Web          | Saxon                                 | HTTP               | admin/admin                                                  |
| Blitzz Technologies      | BWA711                                | HTTP               | admin/admin                                                  |
| BMC                      | Patrol                                | Multi              | patrol/patrol                                                |
| BMC Software             | Servers                               |                    | `Best1_User/BackupU$r`                                       |
| Bomgar                   | Enterprise                            |                    | admin/password                                               |
| Borland                  | Interbase                             |                    | politcally/correct                                           |
| Borland/                 | Interbase                             |                    | SYSDBA/masterkey                                             |
| Boston                   | router simulator                      | HTTP               | admin/admin                                                  |
| Boston                   | router simulator                      | Multi              | (none)/admin                                                 |
| BreezeCOM                | –                                     |                    | (none)/Master                                                |
| Breezecom                | Breezecom Adapters                    |                    | (none)/laflaf                                                |
| Breezecom                | Breezecom Adapters                    |                    | (none)/Master                                                |
| BreezeCOM                | Station Adapter                       |                    | (none)/Super                                                 |
| Brocade                  | Fiberchannel Switches                 | Multi              | admin/password                                               |
| Brocade                  | Fabric OS                             | Multi              | root/fibranne                                                |
| Brocade                  | Silkworm                              | Multi              | admin/brocade1                                               |
| Brother                  | HL-1270n                              |                    | (none)/access                                                |
| Brother                  | NC-3100h                              |                    | (none)/access                                                |
| Brother                  | NC-4100h                              |                    | (none)/access                                                |
| Brother                  | Oce-fx3000                            |                    | admin/access                                                 |
| Brother                  | OCE Imagistics                        |                    | (none)/12345678                                              |
| Brother                  | im9220                                |                    | (none)/00000000                                              |
| Brother                  | ql580N                                |                    | admin/access                                                 |
| BT                       | Voyager 2000                          |                    | admin/admin                                                  |
| BT                       | Voyager                               |                    | admin/admin                                                  |
| BT                       | Home Hub                              |                    | admin/admin                                                  |
| Buffalo/MELCO            | AirStation WLA-L11                    |                    | root/(none)                                                  |
| Busybox                  | Busybox                               |                    | admin/admin                                                  |
| Cabletron                | any                                   |                    | (none)/(none)                                                |
| Cabletron                | Netgear modem/router                  |                    | netman/(none)                                                |
| Cabletron/               | WebView for Matrix E1                 | HTTP               | (none)/(none)                                                |
| Cayman                   | 3220-H DSL Router                     |                    | Any/(none)                                                   |
| Cayman                   | Cayman DSL                            |                    | (none)/(none)                                                |
| Ceragon Networks         | FibeAir                               | Multiple           | root/tooridu                                                 |
| Celerity                 | Mediator                              | Multi              | mediator/mediator                                            |
| Cellit                   | CCPro                                 | Multi              | cellit/cellit                                                |
| CGI World                | Poll It                               | HTTP               | (none)/protection                                            |
| Checkpoint               | SecurePlatform                        | Console            | admin/admin                                                  |
| Chase Research           | Iolan                                 |                    | (blank)/iolan                                                |
| Check Point              | Interspect-all                        | ALL                | admin/admin                                                  |
| Check Point              | SG R70                                | HTTP               | admin/adminadmin                                             |
| Chuming Chen             | NessusWeb                             | HTTP               | administrator/adminpass                                      |
| Ciphertrust              | Ironmail                              | HTTP               | admin/password                                               |
| Cisco                    | 2503                                  |                    | (none)/(none)                                                |
| Cisco                    | 1900                                  | Multi              | (none)/(none)                                                |
| Cisco                    | 2501                                  | Telnet             | (none)/(none)                                                |
| Cisco                    | 3600                                  | Telnet             | (none)/(none)                                                |
| Cisco                    | aironet                               | Multi              | (none)/(none)                                                |
| Cisco                    | Any Router and Switch                 |                    | cisco/cisco                                                  |
| Cisco                    | BBSD MSDE Client                      | Telnet or          | bbsd-client/NULL                                             |
| Cisco                    | BBSM Administrator                    | Multi              | Administrator/changeme                                       |
| Cisco                    | Cache Engine                          | Console            | admin/diamond                                                |
| Cisco                    | CiscoWorks 2000                       |                    | admin/cisco                                                  |
| Cisco                    | CiscoWorks 2000                       |                    | guest/(none)                                                 |
| Cisco                    | ConfigMaker                           |                    | cmaker/cmaker                                                |
| Cisco                    | Content Engine                        | Telnet             | admin/default                                                |
| Cisco                    | Hot Standby                           | HSRP               | (none)/cisco                                                 |
| Cisco                    | IOS                                   | Multi              | cisco/cisco                                                  |
| Cisco                    | IOS                                   | Multi              | (none)/cc                                                    |
| Cisco                    | IOS                                   | Multi              | (none)/Cisco router                                          |
| Cisco                    | IOS                                   | Multi              | (none)/c                                                     |
| Cisco                    | IOS                                   | SNMP               | (none)/cable-docsis                                          |
| Cisco                    | IOS                                   | SNMP               | private/secret                                               |
| Cisco                    | IOS                                   | Multi              | ripeop/(no pw)                                               |
| Cisco                    | MGX                                   |                    | superuser/superuser                                          |
| CISCO                    | N/A                                   |                    | pixadmin/pixadmin                                            |
| Cisco                    | Netranger/secure IDS                  | Multi              | netrangr/attack                                              |
| Cisco                    | Network Registar                      |                    | ADMIN/changeme                                               |
| Cisco                    | pix                                   | Multi              | (none)/(none)                                                |
| Cisco                    | PIX firewall                          | Multi              | (none)/(none)                                                |
| Cisco                    | Router                                | Multi              | (none)/(none)                                                |
| Cisco                    | VPN 3000 Concentrator                 |                    | admin/admin                                                  |
| Cisco-Arrowpoint         | Arrowpoint                            |                    | admin/system                                                 |
| Citrix Systems           | Access Gateway                        | HTTP               | root/rootadmin                                               |
| Citrix Systems           | Access Gateway                        |                    | nsroot/nsroot                                                |
| ClearOne Communications  | Converge                              | HTTP               | ClearOne/RAV                                                 |
| ClearOne Communications  | Converge Pro                          | HTTP               | clearone/clearone                                            |             
| Claris                   | Claris                                |                    | (none)/familymacintosh                                       |
| Cobalt                   | RaQ * Qube*                           |                    | admin/admin                                                  |
| Com21                    | General Equipment(?)                  |                    | (none)/(none)                                                |
| Comcast SMC              | 8014                                  |                    | cusadmin/highspeed                                           |
| Comersus                 | Shopping Cart                         | HTTP               | admin/dmr99                                                  |
| Comersus                 | Shopping Cart                         | HTTP               | admin/dmr99                                                  |
| Colubris Networks        | CN3200/MSC 5100                       | HTTP               | admin/admin                                                  |
| Comodo Group             | MyDLP                                 | HTTP               | mydlp/mydlp                                                  |
| Compaq                   | Familiar Linux                        | telnet/ssh/console | root/rootme                                                  |
| Compaq                   | Armada E500                           | Multi              | Administrator/admin                                          |
| Compaq                   | Armada M700                           | Console            | Administrator/admin                                          |
| Compaq                   | dc770t                                | Multi              | (none)/(none)                                                |
| Compaq                   | Insight Manager                       | Multi              | (none)/(none)                                                |
| Compaq                   | Insight Manager                       |                    | anonymous/(none)                                             |
| Compaq                   | Insight Manager                       |                    | PFCUser/240653C9467E45                                       |
| Compaq                   | Insight Manager                       |                    | user/user                                                    |
| Compaq                   | Management Agents                     |                    | administrator/none                                           |
| Compaq                   | PC BIOS                               | Console            | (none)/Compaq                                                |
| Compualynx               | Cmail Server                          | Multi              | administrator/asecret                                        |
| Compualynx               | Cproxy Server                         | Multi              | administrator/asecret                                        |
| Compualynx               | SCM                                   | Multi              | administrator/asecret                                        |
| Concord                  | PC BIOS                               |                    | (none)/last                                                  |
| Conceptronic             | CADSLR4                               | HTTP/Telnet        | admin/password                                               |
| Conceptronic             | CADSLR4                               | FTP                | anonymous/password                                           |
| Conceptronic             | C100BRS4H                             | HTTP               | admin/1234                                                   |
| Concord                  | PC BIOS                               |                    | (none)/last                                                  |
| Conexant                 | Router                                | HTTP               | admin/(epicrouter/amigosw1/password/conexant)                |
| Control4                 | Home Theater Controller AVMHTC1B      | Telnet             | (none)/ducati900ss                                           |
| Control4                 | Home Theater Controller AVMHTC1B      | Telnet             | root/t0talc0ntr0l4!                                          |
| CoronaMatrix             | phpAddressBook                        | HTTP               | admin/admin                                                  |
| Covertix                 | SmartCipher                           | HTTP               | Admin/Admin                                                  |
| Coyote-Point             | Equaliser 4                           | Serial             | eqadmin/equalizer                                            |
| Coyote-Point             | Equaliser 4                           | Serial             | root/(none)                                                  |
| Crystalview              | OutsideView 32                        |                    | (none)/Crystal                                               |
| Cyberguard               | all firewalls                         | console            | cgadmin/cgadmin                                              |
| CyberMax                 | PC BIOS                               | Console            | (none)/Congress                                              |
| Cyberoam                 | Multiple                              | HTTP               | admin/admin                                                  |
| Cyberoam                 | iView                                 | HTTP               | admin/admin                                                  |
| Cyberoam                 | iView                                 | SSH                | root/admin                                                   |
| Cyclades                 | Cyclades-TS800                        | telnet/ssh/web     | root/(none)                                                  |
| Cyclades                 | Cyclades-TS800                        | HTTP               | root/tslinux                                                 |
| Cyclades                 | PR-1000                               |                    | super/surt                                                   |
| CTX International        | PC BIOS                               | Console            | (none)/CTX_123                                               |
| D-Link                   | DI-701                                | Multi              | (none)/year2000                                              |
| D-Link                   | DI-704                                |                    | (none)/admin                                                 |
| D-Link                   | Dl 604                                | Multi              | admin/(none)                                                 |
| D-Link                   | DWL 900AP                             | Multi              | admin/public                                                 |
| D-Link                   | DWL-900+                              | HTTP               | admin/(none)                                                 |
| D-Link                   | Cable/DSL                             | Multi              | (none)/admin                                                 |
| D-Link                   | DFE-538TX 10/100                      |                    | (none)/(none)                                                |
| D-Link                   | DI-106 ISDN router                    |                    | (none)/1234                                                  |
| D-Link                   | DI-604                                | HTTP               | admin/(none)                                                 |
| D-Link                   | DI-614+                               | HTTP               | user/(none)                                                  |
| Dallas Semiconductors    |                                       | Telnet             | root/tini                                                    |
| Dassault Systemes        | Enovia V6                             |                    | (none)/(none)                                                |
| Daewoo                   | PC BIOS                               | Console            | (none)/Daewuu                                                |
| Data General             | AOS/VS                                | Multi              | operator/operator                                            |
| Data General             | AOS/VS                                | Multi              | op/op                                                        |
| Data General             | AOS/VS                                | Multi              | op/operator                                                  |
| Datacom                  | BSASX/101                             |                    | (none)/letmein                                               |
| Datacom                  | NSBrowse                              | Multi              | sysadm/sysadm                                                |
| Datawizard.net           | FTPXQ server                          | FTP                | test/test                                                    |
| Datawizard.net           | FTPXQ server                          | FTP                | anonymous/any@                                               |
| Davolink                 | DV2020                                | HTTP               | user/user                                                    |
| Davox                    | Unison                                | Multi              | davox/davox                                                  |
| Davox                    | Unison                                | Sybase             | sa/(none)                                                    |
| Daytek                   | PC BIOS                               | Console            | (none)/Daytec                                                |
| Debian                   | Linux LILO Default                    | Console            | (none)/tatercounter2000                                      |
| decnet                   | decnet                                | Multi              | operator/admin                                               |
| Deerfield                | MDaemon                               | HTTP               | MDaemon/MServer                                              |
| Dell                     | bios                                  | Multi              | (none)/(none)                                                |
| Dell                     | c600                                  | Multi              | (none)/(none)                                                |
| Dell                     | cpx h500gt                            | Multi              | (none)/(none)                                                |
| Dell                     | CSr500xt                              | Multi              | (none)/admin                                                 |
| Dell                     | dell latitude cpx                     | Multi              | admin/admin                                                  |
| dell                     | inspiron                              | Multi              | (none)/admin                                                 |
| Dell                     | Latitude                              | Multi              | (none)/1RRWTTOOI                                             |
| Dell                     | LATITUDE                              | Multi              | (none)/(none)                                                |
| Dell                     | latitude c610                         | Multi              | admin/admin                                                  |
| Dell                     | notebook                              | Multi              | (none)/(none)                                                |
| Dell                     | PC BIOS                               | Console            | (none)/Dell                                                  |
| Dell                     | PowerApp Web 100                      | HTTP               | root/powerapp                                                |
| Dell                     | PowerVault 50F                        |                    | root/calvin                                                  |
| Dell                     | TrueMobile 1184                       | HTTP               | admin/admin                                                  |
| Demarc                   | Network Monitor                       | multi              | admin/my_DEMARC                                              |
| Develcon                 | Orbitor Default                       |                    | (none)/password                                              |
| Develcon                 | Orbitor Default                       |                    | (none)/BRIDGE                                                |
| Dictaphone               | ProLog                                |                    | NETOP/(none)                                                 |
| Dictaphone               | ProLog                                |                    | NETWORK/NETWORK                                              |
| Dictaphone               | ProLog                                |                    | PBX/PBX                                                      |
| Digiboard                | Portserver 8 & 16                     |                    | root/dbps                                                    |
| Digicorp                 | Viper                                 | Telnet             | (none)/password                                              |
| Digicorp                 | Viper                                 | Telnet             | (none)/BRIDGE                                                |
| Digital                  | 44175                                 | Multi              | 2/maintain                                                   |
| Digital                  | 44175                                 | Multi              | 2/maintain                                                   |
| Digicraft Software       | Yak!                                  | FTP                | Yak/asd123                                                   |
| Digium                   | AsteriskNOW                           | HTTP               | admin/password                                               |
| Divar                    | XF                                    | HTTP               | admin/(none)                                                 |
| Divar                    | XF                                    | HTTP               | viewer/(none)                                                |
| Digital Equipment        | 10-Dec                                | Multi              | 1/syslib                                                     |
| Digital Equipment        | 10-Dec                                | Multi              | 1/operator                                                   |
| Digital Equipment        | 10-Dec                                | Multi              | 1/manager                                                    |
| Digital Equipment        | 10-Dec                                | Multi              | 2/maintain                                                   |
| Digital Equipment        | 10-Dec                                | Multi              | 2/syslib                                                     |
| Digital Equipment        | 10-Dec                                | Multi              | 2/manager                                                    |
| Digital Equipment        | 10-Dec                                | Multi              | 2/operator                                                   |
| Digital Equipment        | 10-Dec                                | Multi              | 30/games                                                     |
| Digital Equipment        | 10-Dec                                | Multi              | 5/games                                                      |
| Digital Equipment        | 10-Dec                                | Multi              | 7/maintain                                                   |
| Digital Equipment        | DecServer                             | Multi              | (none)/ACCESS                                                |
| Digital Equipment        | DecServer                             | Multi              | (none)/SYSTEM                                                |
| Digital Equipment        | IRIS                                  | Multi              | accounting/accounting                                        |
| Digital Equipment        | IRIS                                  | Multi              | boss/boss                                                    |
| Digital Equipment        | IRIS                                  | Multi              | demo/demo                                                    |
| Digital Equipment        | IRIS                                  | Multi              | manager/manager                                              |
| Digital Equipment        | IRIS                                  | Multi              | PDP11/PDP11                                                  |
| Digital Equipment        | IRIS                                  | Multi              | PDP8/PDP8                                                    |
| Digital Equipment        | IRIS                                  | Multi              | software/software                                            |
| Digital Equipment        | PC BIOS                               | Console            | (none)/komprie                                               |
| Digital Equipment        | RSX                                   | Multi              | 1/1                                                          |
| Digital Equipment        | RSX                                   | Multi              | BATCH/BATCH                                                  |
| Digital Equipment        | RSX                                   | Multi              | SYSTEM/MANAGER                                               |
| Digital Equipment        | RSX                                   | Multi              | SYSTEM/SYSTEM                                                |
| Digital Equipment        | RSX                                   | Multi              | USER/USER                                                    |
| Digital Equipment        | Terminal Server                       | Multi              | USER/USER                                                    |
| Digital Equipment        | Terminal Server                       | Multi              | USER/USER                                                    |
| Dlink                    | DFE-538TX                             |                    | (none)/(none)                                                |
| DLink                    | DI-206 ISDN router                    |                    | Admin/Admin                                                  |
| Dlink                    | Dl-106 ISDN router                    |                    | (none)/1234                                                  |
| Dupont                   | Digital Water Proofer                 | Telnet             | root/par0t                                                   |
| Dupont                   | Digital Water Proofer                 | Telnet             | root/par0t                                                   |
| Ducati Motor Holding     | Diavel                                | Console            | (none)/Last 4 digits of VIN                                  |
| DotNetNuke Corporation   | DotNetNuke                            | HTTP               | host/dnnhost                                                 |
| DotNetNuke Corporation   | DotNetNuke                            | HTTP               | admin/dnnadmin                                               |
| Draytek                  | Vigor3300v                            | HTTP               | Draytek/1234                                                 |
| Draytek Corp             | Vigor2200USB                          |                    | admin/(none)                                                 |
| Draytek Corp             | Vigor2600 Plus Series Annex A         |                    | admin/(none)                                                 |
| DVB                      | DVstation                             | HTTP/VNC           | dvstation/dvst10n                                            |
| DVB                      | DVstation                             | SSH                | root/pixmet2003                                              |
| Dynalink                 | RTA020                                | Multi              | admin/admin                                                  |
| Dynalink                 | RTA230                                | Multi              | userNotUsed/userNotU                                         |
| Dynix Library Systems    | Dynix                                 | Multi              | circ/(none)                                                  |
| Dynix Library Systems    | Dynix                                 | Multi              | LIBRARY/(none)                                               |
| Dynix Library Systems    | Dynix                                 | Multi              | SETUP/(none)                                                 |
| E-Tech                   | ADSL Ethernet Router                  | HTTP               | admin/epicrouter                                             |
| ECI                      | Any                                   |                    | (none)/(none)                                                |
| Efficient                | –                                     |                    | (none)/(none)                                                |
| Efficient                | –                                     |                    | (none)/(none)                                                |
| Elron                    | Firewall                              |                    | hostname//sysadmin                                           |
| Elsa                     | LANCom Office                         | Telnet             | (none)/cisco                                                 |
| emai                     | hotmail                               |                    | (none)/(none)                                                |
| enCAD                    | XPO                                   | Multi              | (none)/(none)                                                |
| Enterasys                | (1G694-13 or 1G582-09                 |                    | /                                                            |
| Enox                     | PC BIOS                               | Console            | (none)/xo11nE                                                |
| Enterasys                | ANG-1105                              | Telnet             | (none)/netadmin                                              |
| Epox                     | PC BIOS                               | Console            | (none)/central                                               |
| Ericsson                 | ACC                                   |                    | netman/netman                                                |
| Ericsson                 | md110 pabx                            | Multi              | (none)/help                                                  |
| Ericsson                 | ACC                                   |                    | netman/netman                                                |
| Ericsson                 | md110 pabx                            | Multi              | (none)/help                                                  |
| Ericsson                 | ACC                                   |                    | netman/netman                                                |
| Ericsson                 | md110 pabx                            | Multi              | (none)/help                                                  |
| Erpepe                   | ADSL Router                           | Telnet             | chochete/tiabuena                                            |
| EverFocus                | PowerPlex                             | Multi              | admin/admin                                                  |
| EverFocus                | PowerPlex                             | Multi              | supervisor/supervisor                                        |
| Extreme                  | All                                   |                    | Admin/(none)                                                 |
| Extreme                  | All                                   |                    | Admin/(none)                                                 |
| F5-Networks              | BIGIP                                 | Multi              | (none)/(none)                                                |
| Fastwire                 | Fastwire Bank Transfer                | N/A                | fastwire/fw                                                  |
| FiberDriver              | N-Base Switches                       | Multi              | /forgot                                                      |
| Flowpoint                | 2200                                  |                    | (none)/Serial Num                                            |
| Flowpoint                | 144, 2200 DSL Routers                 |                    | (none)/password                                              |
| Flowpoint                | 2200 SDSL                             | Telnet             | admin/admin                                                  |
| Flowpoint                | DSL                                   | Telnet             | admin/admin                                                  |
| Flowpoint                | Flowpoint 2200                        | Telnet             | (none)/Serial Number                                         |
| Freetech                 | PC BIOS                               | Console            | (none)/Posterie                                              |
| fujitsu                  | l460                                  |                    | (none)/(none)                                                |
| fujitsu                  | l460                                  |                    | (none)/(none)                                                |
| Galacticomm              | Major BBS                             | Multi              | Sysop/Sysop                                                  |
| Gateway                  | Solo                                  | Multi              | (none)/(none)                                                |
| gatway                   | solo9100                              |                    | (none)/(none)                                                |
| Gigabyte                 | Gigabyte                              | Multi              | (none)/(none)                                                |
| glFtpD                   | glFtpD                                | Console            | glftpd/glftpd                                                |
| GoNET                    | General Equipment(?)                  |                    | fast/adb234                                                  |
| GuardOne                 | BizGuard                              | Multi              | n.a/guardone                                                 |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | ADVMAIL/HPOFFICE DATA                                        |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | ADVMAIL/HP                                                   |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | FIELD/MGR                                                    |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | FIELD/MANAGER                                                |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | FIELD/LOTUS                                                  |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | FIELD/HPONLY                                                 |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | HELLO/MANAGER.SYS                                            |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | HELLO/FIELD.SUPPORT                                          |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MAIL/REMOTE                                                  |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MAIL/HPOFFICE                                                |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MAIL/MAIL                                                    |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MANAGER/SYS                                                  |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MANAGER/ITF3000                                              |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MANAGER/COGNOS                                               |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGE/VESOFT                                                   |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/CAROLIAN                                                 |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/XLSERVER                                                 |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/TELESUP                                                  |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/CCC                                                      |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/WORD                                                     |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/ROBELLE                                                  |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/HPONLY                                                   |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/HPP189                                                   |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/INTX3                                                    |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/NETBASE                                                  |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | MGR/RJE                                                      |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | OPERATOR/SYS                                                 |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | OPERATOR/SYSTEM                                              |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | OPERATOR/COGNOS                                              |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | RSBCMON/SYS                                                  |
| Hewlett-Packard          | HP 2000/3000 MPE/xx                   | Multi              | WP/HPOFFICE                                                  |
| Hewlett-Packard          | LaserJet Net Printers                 | Telnet             | (none)/(none)                                                |
| Hewlett-Packard          | LaserJet Net Printers                 | 9100               | (none)/(none)                                                |
| Hewlett-Packard          | notebook                              | Multi              | (none)/(none)                                                |
| Hewlett-Packard          | omnibook                              | Multi              | (none)/admin                                                 |
| Hewlett-Packard          | omnibook 4150b                        | Multi              | (none)/(nessun)                                              |
| Hewlett-Packard          | Omnibook XE3                          | Multi              | (none)/(none)                                                |
| Hewlett-Packard          | omnibook6000                          | Multi              | (none)/(none)                                                |
| Hewlett-Packard          | Vectra                                | Console            | (none)/hewlpack                                              |
| Hewlett-Packard          | Vectra                                | Console            | (none)/hewlpack                                              |
| IBM                      | 2210                                  |                    | def/trade                                                    |
| IBM                      | 2628                                  | Multi              | (none)/(none)                                                |
| IBM                      | 390e                                  | Multi              | (none)/admin                                                 |
| IBM                      | 600x                                  | Multi              | (none)/admin                                                 |
| IBM                      | 8225                                  | Multi              | I5rDv2b2JjA8Mm/A52896nG93096a                                |
| IBM                      | 8239 Token Ring HUB                   | Console            | (none)/R1QTPS                                                |
| IBM                      | a20m                                  | Multi              | (none)/admin                                                 |
| IBM                      | A21m                                  | Multi              | (none)/(none)                                                |
| IBM                      | AIX                                   | Multi              | guest/(none)                                                 |
| IBM                      | AIX                                   | Multi              | root/ibm                                                     |
| IBM                      | AS/400                                |                    | qpgmr/qpgmr                                                  |
| IBM                      | AS/400                                |                    | QUSER/QUSER                                                  |
| IBM                      | AS400                                 |                    | QSRV/QSRV                                                    |
| IBM                      | Ascend OEM Routers                    | Telnet             | (none)/ascend                                                |
| IBM                      | DB2                                   |                    | db2admin/db2admin                                            |
| IBM                      | LAN Server / OS/2                     |                    | username/password                                            |
| IBM                      | Lotus Domino Go                       |                    | webadmin/webibm                                              |
| IBM                      | OS/400                                | Multi              | 11111111/11111111                                            |
| IBM                      | OS/400                                | Multi              | ibm/password                                                 |
| IBM                      | OS/400                                | Multi              | ibm/service                                                  |
| IBM                      | OS/400                                | Multi              | qsecofr/qsecofr                                              |
| IBM                      | OS/400                                | Multi              | qsecofr/22222222                                             |
| IBM                      | OS/400                                | Multi              | qsrv/qsrv                                                    |
| IBM                      | OS/400                                | Multi              | qsvr/qsvr                                                    |
| IBM                      | OS/400                                | Multi              | qsysopr/qsysopr                                              |
| IBM                      | OS/400                                | Multi              | secofr/secofr                                                |
| IBM                      | OS/400                                | Multi              | sysopr/sysopr                                                |
| IBM                      | PC BIOS                               | Console            | (none)/IBM                                                   |
| IBM                      | PC BIOS                               | Console            | (none)/sertafu                                               |
| IBM                      | POS CMOS                              | Console            | ESSEX/(none)                                                 |
| IBM                      | ra6000                                |                    | (none)/(none)                                                |
| IBM                      | RS/6000                               |                    | root/ibm                                                     |
| IBM                      | switch                                | Telnet             | admin/(none)                                                 |
| IBM                      | thinkpad                              | Multi              | (none)/(none)                                                |
| IBM                      | Tivoli                                | HTTP               | admin/admin                                                  |
| IBM                      | TotalStorage                          | Multi              | storwatch/specialist                                         |
| IBM                      | VM/CMS                                | Multi              | $ALOC$/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | AP2SVP/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | AUTOLOG1/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | BATCH1/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | CCC/(none)                                                   |
| IBM                      | VM/CMS                                | Multi              | CMSUSER/(none)                                               |
| IBM                      | VM/CMS                                | Multi              | CPRM/(none)                                                  |
| IBM                      | VM/CMS                                | Multi              | CVIEW/(none)                                                 |
| IBM                      | VM/CMS                                | Multi              | DEMO1/(none)                                                 |
| IBM                      | VM/CMS                                | Multi              | DEMO3/(none)                                                 |
| IBM                      | VM/CMS                                | Multi              | DIRECT/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | DISKCNT/(none)                                               |
| IBM                      | VM/CMS                                | Multi              | FSFADMIN/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | FSFTASK2/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | IDMS/(none)                                                  |
| IBM                      | VM/CMS                                | Multi              | IIPS/(none)                                                  |
| IBM                      | VM/CMS                                | Multi              | ISPVM/(none)                                                 |
| IBM                      | VM/CMS                                | Multi              | IVPM2/(none)                                                 |
| IBM                      | VM/CMS                                | Multi              | MOESERV/(none)                                               |
| IBM                      | VM/CMS                                | Multi              | OLTSEP/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | OPERATNS/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | PENG/(none)                                                  |
| IBM                      | VM/CMS                                | Multi              | PRODBM/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | PSFMAINT/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | RDM470/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | RSCS/(none)                                                  |
| IBM                      | VM/CMS                                | Multi              | SAVSYS/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | SFCNTRL/(none)                                               |
| IBM                      | VM/CMS                                | Multi              | SQLDBA/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | SYSADMIN/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | SYSDUMP1/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | SYSWRM/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | TEMP/(none)                                                  |
| IBM                      | VM/CMS                                | Multi              | VASTEST/(none)                                               |
| IBM                      | VM/CMS                                | Multi              | VMARCH/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | VMASSYS/(none)                                               |
| IBM                      | VM/CMS                                | Multi              | VMBSYSAD/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | VMTAPE/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | VMUTIL/(none)                                                |
| IBM                      | VM/CMS                                | Multi              | VSEMAINT/(none)                                              |
| IBM                      | VM/CMS                                | Multi              | VTAM/(none)                                                  |
| Iiawmd                   | web page                              | HTTP               | (none)/(none)                                                |
| Informix                 | Database                              | N/A                | informix/informix                                            |
| Intel                    | 460T Express Switch                   | Multi              | (none)/(none)                                                |
| Intel                    | 510T                                  |                    | (none)/admin                                                 |
| Intel                    | All Routers                           |                    | (none)/babbit                                                |
| Intel                    | Express 9520 Router                   | Multi              | NICONEX/NICONEX                                              |
| Intel                    | lan rover                             | Console            | root/admin                                                   |
| Intel                    | LanRover VPN                          | Multi              | (none)/shiva                                                 |
| Intel                    | netstructure                          | Telnet             | admin/(none)                                                 |
| Intel                    | Shiva                                 | Multi              | root/(none)                                                  |
| Intel                    | Wireless AP 2011                      | Multi              | (none)/Intel                                                 |
| Intel                    | wireless lan                          |                    | (none)/comcomcom                                             |
| Interbase                | Interbase Database                    | Multi              | SYSDBA/masterkey                                             |
| Intershop                | Intershop                             | HTTP               | operator/$chwarzepumpe                                       |
| Intex                    | organizer                             | Multi              | (none)/(none)                                                |
| Ipswitch                 | Whats up Gold                         |                    | admin/admin                                                  |
| IRC                      | IRC Daemon                            | IRC                | (none)/FOOBAR                                                |
| IRCXPro                  | IRCXPro Server                        | IRC                | admin/password                                               |
| IRIS                     |                                       | PDP11              | PDP11/User                                                   |
| Iwill                    | PC BIOS                               | Console            | (none)/iwill                                                 |
| Jetform                  | Jetform Design                        | HTTP               | Jetform/(none)                                               |
| JetWay                   | PC BIOS                               | Console            | (none)/spooml                                                |
| Juniper                  | All                                   |                    | root/none                                                    |
| kaptest                  | usmle                                 | HTTP               | admin/(none)                                                 |
| Kawa                     | All                                   |                    | (none)/(none)                                                |
| Knox                     | Arkeia Server                         |                    | root/(none)                                                  |
| Kyocera                  | EcoLink                               | HTTP               | (none)/PASSWORD                                              |
| LANCAST                  | All                                   |                    | (none)/(none)                                                |
| LANCOM                   | IL11                                  | Multi              | (none)/(none)                                                |
| Lantronics               | Lantronics Terminal                   | TCP 7000           | (none)/access                                                |
| Lantronix                | LPS1-T Print Server                   | TCP 7000           | any/system                                                   |
| Lantronix                | LSB4                                  | TCP 7000           | (none)/system                                                |
| Lantronix                | MSS110, MSSVIA,                       | TCP 7000           | (none)/system                                                |
| Lantronix                | Terminal Server                       | TCP 7000           | (none)/access                                                |
| Lantronix                | Terminal Server                       | TCP 7000           | (none)/lantronix                                             |
| LGIC                     | Goldstream                            |                    | LR-ISDN/LR-ISDN                                              |
| Linksys                  | BEFSR41                               | HTTP               | (none)/admin                                                 |
| Linksys                  | BEFW11S4                              | HTTP               | admin/(none)                                                 |
| Linksys                  | DSL                                   | Telnet             | (none)/admin                                                 |
| Linksys                  | EtherFast Cable/DSL                   | Multi              | Administrator/admin                                          |
| LinkSys                  | WAP11                                 | Multi              | (none)/(none)                                                |
| Linunx                   | Linux                                 | Console            | Administrator/admin                                          |
| Linux                    | Bankmandiri.co.id                     | HTTP               | Administrator/(none)                                         |
| Linux                    | Slackware                             | Multi              | satan/(none)                                                 |
| Linux                    | UCLinux for UCSIMM                    | Multi              | root/uClinux                                                 |
| Livingston               | IRX Router                            | Telnet             | !root/(none)                                                 |
| Livingston               | Livingston                            |                    | !root/blank                                                  |
| Livingston               | Officerouter                          | Telnet             | !root/(none)                                                 |
| Lucent                   | Anymedia                              | Console            | LUCENT01/UI-PSWD-01                                          |
| Lucent                   | Anymedia                              | Console            | LUCENT02/UI-PSWD-02                                          |
| Lucent                   | AP-1000                               |                    | public/public                                                |
| Lucent                   | AP-1000                               |                    | public/private                                               |
| Lucent                   | B-STDX9000                            | Multi              | (any 3/cascade                                               |
| Lucent                   | B-STDX9000                            | debug mode         | (none)/cascade                                               |
| Lucent                   | B-STDX9000                            | debug mode         | (none)/cascade                                               |
| Lucent                   | Cajun Family                          |                    | root/root                                                    |
| Lucent                   | Cajun Family                          |                    | root/root                                                    |
| Lucent                   | CBX 500                               | Multi              | (any 3/cascade                                               |
| Lucent                   | CBX 500                               | SNMP               | (none)/cascade                                               |
| Lucent                   | CBX 500                               | SNMP               | (none)/cascade                                               |
| lucent                   | dsl                                   |                    | (none)/(none)                                                |
| Lucent                   | GX 550                                | Multi              | (any 3/cascade                                               |
| Lucent                   | GX 550                                | debug              | (none)/cascade                                               |
| Lucent                   | GX 550                                | SNMP               | (none)/cascade                                               |
| Lucent                   | MAX                                   | Multi              | (none)/(none)                                                |
| Lucent                   | MAX-TNT                               | Multi              | admin/Ascend                                                 |
| Lucent                   | Packetstar (PSAX)                     |                    | readwrite/lucenttech1                                        |
| Lucent                   | Packetstar (PSAX)                     |                    | readwrite/lucenttech1                                        |
| Lucent                   | Portmaster 2                          |                    | !root/none                                                   |
| Lucent                   | Portmaster 2                          |                    | !root/none                                                   |
| lucent                   | Portmaster 3                          |                    | !root/!ishtar                                                |
| lucent                   | Portmaster 3                          |                    | !root/!ishtar                                                |
| Lucent                   | PSAX 1200 and below                   | Multi              | root/ascend                                                  |
| Lucent                   | PSAX 1250 and above                   | Multi              | readonly/lucenttech2                                         |
| Lucent                   | PSAX 1250 and above                   | Multi              | readwrite/lucenttech1                                        |
| lxy_nrg                  | 87418                                 | Multi              | (none)/(none)                                                |
| M-M-O                    | Webrealm                              | HTTP               | Administrator/admin                                          |
| MachSpeed                | PC BIOS                               | Console            | (none)/sp99dd                                                |
| Macromedia               | Dreamweaver                           | FTP                | (none)/admin                                                 |
| MacSense                 | X-Router Pro                          |                    | admin/admin                                                  |
| Magic-Pro                | PC BIOS                               | Console            | (none)/prost                                                 |
| Mambo                    | Site Server                           | HTTP               | admin/admin                                                  |
| Megastar                 | PC BIOS                               | Console            | (none)/star                                                  |
| Mentec                   | Micro/RSX                             | Multi              | MICRO/RSX                                                    |
| MERCURY                  | 234234                                | SNMP               | Administrator/admin                                          |
| MERCURY                  | 234234                                | SNMP               | Administrator/admin                                          |
| Meridian                 | PBX                                   | Telnet             | service/smile                                                |
| microcom                 | hdms                                  |                    | system/hdms                                                  |
| Micron                   | –                                     |                    | (none)/(none)                                                |
| Micron                   | PC BIOS                               | Console            | (none)/xyzall                                                |
| Micronet                 | Access Point                          | Telnet             | root/default                                                 |
| Micronics                | PC BIOS                               | Console            | (none)/dn_04rjc                                              |
| Microplex                | Print Server                          | Telnet             | root/root                                                    |
| microRouter              | 900i                                  | Console/           | (none)/letmein                                               |
| microRouter              | 900i                                  | Console/           | (none)/letmein                                               |
| Microsoft                | Base Station Access                   | HTTP               | (none)/admin                                                 |
| Microsoft                | MN-500 Wireless                       | Multi              | admin/admin                                                  |
| MICROSOFT                | NT                                    |                    | free user/user                                               |
| Microsoft                | SQL Server                            | Multi              | sa/(blank)                                                   |
| Microsoft                | Windows NT                            | Multi              | (null)/(none)                                                |
| Microsoft                | Windows NT                            |                    | Administrator/(none)                                         |
| Microsoft                | Windows NT                            |                    | Guest/(none)                                                 |
| Microsoft                | Windows NT                            | Multi              | Guest/(none)                                                 |
| Microsoft                | Windows NT                            |                    | Mail/(none)                                                  |
| Microsoft                | Windows NT                            | Multi              | User/User                                                    |
| Mintel                   | Mintel PBX                            |                    | (none)/SYSTEM                                                |
| Mitel                    | 3300 ICP                              | HTTP               | system/password                                              |
| Motorola                 | Cablerouter                           | Telnet             | cablecom/router                                              |
| Motorola                 | Motorola-Cablerouter                  |                    | cablecom/router                                              |
| msdloto                  | msdloto                               |                    | (none)/(none)                                                |
| Multi-Tech               | ProxyServer                           | Multi              | supervisor/(none)                                            |
| MySQL                    | MySQL                                 | Any                | root/(none)                                                  |
| Nanoteq                  | NetSeq firewall                       |                    | admin/NetSeq                                                 |
| NCR                      | NCR UNIX                              | Multi              | ncrm/ncrm                                                    |
| NetApp                   | NetCache                              |                    | admin/NetCache                                               |
| Netgaer                  | RH328                                 |                    | (none)/1234                                                  |
| Netgear                  | ISDN-Router RH348                     |                    | (none)/1234                                                  |
| Netgear                  | RH338                                 | HTTP               | (none)/1234                                                  |
| Netgear                  | RH438 /                               | HTTP               | (none)/1234                                                  |
| Netgear                  | RP114                                 | Telnet             | (none)/1234                                                  |
| Netgear                  | RP614                                 | HTTP               | admin/password                                               |
| Netgear                  | RT311                                 | HTTP               | admin/1234                                                   |
| Netgear                  | RT314                                 |                    | Admin/1234                                                   |
| Netgear                  | RT338                                 |                    | (none)/1234                                                  |
| NetGenesis               | NetAnalysis Web                       | HTTP               | naadmin/naadmin                                              |
| netlink                  | rt314                                 |                    | (none)/(none)                                                |
| Netopia                  | 455                                   |                    | (none)/(none)                                                |
| Netopia                  | Netopia 9500                          | Telnet             | netopia/netopia                                              |
| Netopia                  | R910                                  | Multi              | admin/(none)                                                 |
| Netport                  | Express 10/100                        | multi              | setup/setup                                                  |
| Netscape                 | Netscape                              | HTTP               | admin/admin                                                  |
| Netscreen                | –                                     |                    | netscreen/netscreen                                          |
| Netscreen                | firewall                              | Multi              | admin/(none)                                                 |
| Netscreen                | firewall                              | Telnet             | Administrator/(none)                                         |
| Netscreen                | firewall                              | Telnet             | operator/(none)                                              |
| Netscreen                | NS-5, NS10, NS-100                    |                    | netscreen/netscreen                                          |
| NetworkICE               | ICECap Manager                        | 8081               | iceman/(none)                                                |
| NeXT                     | –                                     |                    | me/(none)                                                    |
| NeXT                     | NeXTStep                              | Multi              | root/NeXT                                                    |
| NGSec                    | NGSecureWeb                           | HTTP               | admin/(none)                                                 |
| NGSec                    | NGSecureWeb                           | HTTP               | admin/asd                                                    |
| Nimble                   | PC BIOS                               | Console            | (none)/xdfk9874t3                                            |
| Nokia                    | DSL Router M1122                      | Multi              | m1122/m1122                                                  |
| Nokia                    | MW1122                                | Multi              | telecom/telecom                                              |
| Norman                   | 5.3                                   | Multi              | (none)/(none)                                                |
| Nortel                   | Accelar (Passport) 1000               | Multi              | l2/l2                                                        |
| Nortel                   | Accelar (Passport) 1000               | Multi              | ro/ro                                                        |
| Nortel                   | Accelar (Passport) 1000               | Multi              | rwa/rwa                                                      |
| Nortel                   | Bay                                   | Console            | (none)/(none)                                                |
| Nortel                   | Baystack 450T                         |                    | (none)/secure                                                |
| Nortel                   | Contivity Extranet                    |                    | admin/setup                                                  |
| Nortel                   | Extranet Switches                     | Multi              | admin/setup                                                  |
| Nortel                   | Matra 6501 PBX                        | Console            | (none)/0                                                     |
| Nortel                   | Meridian 1 PBX                        |                    | 0/0                                                          |
| Nortel                   | Meridian CCR                          | Multi              | ccrusr/ccrusr                                                |
| Nortel                   | Meridian CCR                          | Multi              | service/smile                                                |
| Nortel                   | Meridian Link                         | Multi              | maint/maint                                                  |
| Nortel                   | Meridian Link                         | Multi              | service/smile                                                |
| Nortel                   | Meridian MAX                          | Multi              | root/3ep5w2u                                                 |
| Nortel                   | Meridian PBX                          | Serial             | login/0                                                      |
| Nortel                   | Meridian PBX                          | Serial             | login/8429                                                   |
| Nortel                   | Meridian PBX                          | Serial             | spcl/0                                                       |
| Nortel                   | Norstar Modular ICS                   |                    | **ADMIN/ADMIN (23646)                                        |
| Nortel                   | Remote Annex 2000                     |                    | admin/(ip address)                                           |
| Nortel                   | Shasta                                |                    | admin/admin                                                  |
| Nortel                   | Baystack 450T                         |                    | (none)/secure                                                |
| Nortel                   | Accelar (Passport) 1000               | Multi              | l2/l2                                                        |
| Nortel                   | Accelar (Passport) 1000               | Multi              | ro/ro                                                        |
| Nortel                   | Accelar (Passport) 1000               | Multi              | rwa/rwa                                                      |
| Nortel                   | Bay                                   | Console            | (none)/(none)                                                |
| Nortel                   | Baystack 450T                         |                    | (none)/secure                                                |
| Nortel                   | Contivity Extranet                    |                    | admin/setup                                                  |
| Nortel                   | Extranet Switches                     | Multi              | admin/setup                                                  |
| Nortel                   | Matra 6501 PBX                        | Console            | (none)/0                                                     |
| Nortel                   | Meridian 1 PBX                        |                    | 0/0                                                          |
| Nortel                   | Meridian CCR                          | Multi              | ccrusr/ccrusr                                                |
| Nortel                   | Meridian CCR                          | Multi              | service/smile                                                |
| Nortel                   | Meridian Link                         | Multi              | maint/maint                                                  |
| Nortel                   | Meridian Link                         | Multi              | service/smile                                                |
| Nortel                   | Meridian MAX                          | Multi              | root/3ep5w2u                                                 |
| Nortel                   | Meridian PBX                          | Serial             | login/0                                                      |
| Nortel                   | Meridian PBX                          | Serial             | login/8429                                                   |
| Nortel                   | Meridian PBX                          | Serial             | spcl/0                                                       |
| Nortel                   | Norstar Modular ICS                   |                    | **ADMIN/ADMIN (23646)                                        |
| Nortel                   | Remote Annex 2000                     |                    | admin/(ip address)                                           |
| Nortel                   | Shasta                                |                    | admin/admin                                                  |
| Nortel                   | Baystack 450T                         |                    | (none)/secure                                                |
| Nortel                   | Accelar (Passport) 1000               | Multi              | l2/l2                                                        |
| Nortel                   | Accelar (Passport) 1000               | Multi              | ro/ro                                                        |
| Nortel                   | Accelar (Passport) 1000               | Multi              | rwa/rwa                                                      |
| Nortel                   | Bay                                   | Console            | (none)/(none)                                                |
| Nortel                   | Baystack 450T                         |                    | (none)/secure                                                |
| Nortel                   | Contivity Extranet                    |                    | admin/setup                                                  |
| Nortel                   | Extranet Switches                     | Multi              | admin/setup                                                  |
| Nortel                   | Matra 6501 PBX                        | Console            | (none)/0                                                     |
| Nortel                   | Meridian 1 PBX                        |                    | 0/0                                                          |
| Nortel                   | Meridian CCR                          | Multi              | ccrusr/ccrusr                                                |
| Nortel                   | Meridian CCR                          | Multi              | service/smile                                                |
| Nortel                   | Meridian Link                         | Multi              | maint/maint                                                  |
| Nortel                   | Meridian Link                         | Multi              | service/smile                                                |
| Nortel                   | Meridian MAX                          | Multi              | root/3ep5w2u                                                 |
| Nortel                   | Meridian PBX                          | Serial             | login/0                                                      |
| Nortel                   | Meridian PBX                          | Serial             | login/8429                                                   |
| Nortel                   | Meridian PBX                          | Serial             | spcl/0                                                       |
| Nortel                   | Norstar Modular ICS                   |                    | **ADMIN/ADMIN (23646)                                        |
| Nortel                   | Remote Annex 2000                     |                    | admin/(ip address)                                           |
| Nortel                   | Shasta                                |                    | admin/admin                                                  |
| Nortel                   | Baystack 450T                         |                    | (none)/secure                                                |
| novell                   | –                                     |                    | (none)/(none)                                                |
| Novell                   | iChain                                | Console            | (none)/san fran 8                                            |
| Novell                   | iChain/ICS                            | Telnet             | (none)/root                                                  |
| Novell                   | Netware                               | Multi              | ADMIN/ADMIN                                                  |
| Novell                   | Netware                               | Multi              | ARCHIVIST/(none)                                             |
| Novell                   | Netware                               | Multi              | BACKUP/(none)                                                |
| Novell                   | NetWare                               |                    | CHEY_ARCHSVR/WONDERLAND                                      |
| Novell                   | Netware                               | Multi              | CHEY_ARCHSVR/(none)                                          |
| Novell                   | Netware                               | Multi              | FAX/(none)                                                   |
| Novell                   | Netware                               | Multi              | FAXUSER/(none)                                               |
| Novell                   | Netware                               | Multi              | FAXWORKS/FAXWORKS                                            |
| Novell                   | NetWare                               |                    | GATEWAY/(none)                                               |
| Novell                   | Netware                               | Multi              | GATEWAY/(none)                                               |
| Novell                   | Netware                               | Multi              | GUEST/GUESTGUEST                                             |
| Novell                   | Netware                               | Multi              | GUEST/GUEST                                                  |
| Novell                   | Netware                               | Multi              | HPLASER/(none)                                               |
| Novell                   | Netware                               | Multi              | LASER/(none)                                                 |
| Novell                   | Netware                               | Multi              | LASERWRITER/LASERWRITER                                      |
| Novell                   | Netware                               | Multi              | MAIL/(none)                                                  |
| Novell                   | Netware                               | Multi              | POST/(none)                                                  |
| Novell                   | Netware                               | Multi              | PRINT/(none)                                                 |
| Novell                   | Netware                               | Multi              | PRINTER/(none)                                               |
| Novell                   | Netware                               | Multi              | ROOT/(none)                                                  |
| Novell                   | Netware                               | Multi              | ROUTER/(none)                                                |
| Novell                   | Netware                               | Multi              | SUPERVISOR/NETFRAME                                          |
| Novell                   | Netware                               | Multi              | SUPERVISOR/NF                                                |
| Novell                   | Netware                               | Multi              | SUPERVISOR/SUPERVISOR                                        |
| Novell                   | Netware                               | Multi              | SUPERVISOR/SYSTEM                                            |
| Novell                   | Netware                               | Multi              | TEST/(none)                                                  |
| Novell                   | Netware                               | Multi              | USER_TEMPLATE/USER_TEMPLATE                                  |
| Novell                   | Netware                               | Multi              | WANGTEK/WANGTEK                                              |
| Novell                   | Netware                               | Multi              | WINDOWS_/WINDOWS_PASSTHRU                                    |
| Novell                   | Netware                               | Multi              | WINSABRE/SABRE                                               |
| Nurit                    | PC BIOS                               | Console            | $system/(none)                                               |
| OCE                      | Printers                              | HTTP               | (none)/0 and the number of OCE printer                       |
| ODS                      | 1094 IS Chassis                       |                    | ods/ods                                                      |
| Omuron                   | MR104FH                               | Multi              | (none)/(none)                                                |
| Openwave                 | MSP                                   | HTTP               | cac_admin/cacadmin                                           |
| Optivision               | Nac 3000 & 4000                       |                    | root/mpegvideo                                               |
| Optus                    | Counter-Strike                        | Multi              | Administrator/admin                                          |
| Oracle                   | 7 or later                            |                    | Scott/Tiger                                                  |
| Oracle                   | 7 or later                            |                    | system/manager                                               |
| Oracle                   | 8i                                    |                    | internal/oracle                                              |
| Oracle                   | Finacial Package                      | SAP                | SAPR3/SAP                                                    |
| Oracle                   | Oracle RDBMS                          | Multi              | ADAMS/WOOD                                                   |
| Oracle                   | Oracle RDBMS                          | Multi              | APPS/APPS                                                    |
| Oracle                   | Oracle RDBMS                          | Multi              | AQUSER/AQUSER                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | AURORA@/INVALID                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | CATALOG/CATALOG                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | CDEMOCOR/CDEMOCOR                                            |
| Oracle                   | Oracle RDBMS                          | Multi              | CDEMOUCB/CDEMOUCB                                            |
| Oracle                   | Oracle RDBMS                          | Multi              | COMPANY/COMPANY                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | CTXSYS/CTXSYS                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | DBSNMP/DBSNMP                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | DEMO8/DEMO8                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | EVENT/EVENT                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | FND/FND                                                      |
| Oracle                   | Oracle RDBMS                          | Multi              | GPLD/GPLD                                                    |
| Oracle                   | Oracle RDBMS                          | Multi              | MDSYS/MDSYS                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | MILLER/MILLER                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | MODTEST/YES                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | MTYSYS/MTYSYS                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | (none)/(none)                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | NAMES/NAMES                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | ORDPLUGINS/ORDPLUGINS                                        |
| Oracle                   | Oracle RDBMS                          | Multi              | OUTLN/OUTLN                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | POWERCARTUSER/POWERCARTUSER                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | PUBSUB/PUBSUB                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | RMAIL/RMAIL                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | SAMPLE/SAMPLE                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | SECDEMO/SECDEMO                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | SYSADM/SYSADM                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | SYSTEM/MANAGER                                               |
| Oracle                   | Oracle RDBMS                          | Multi              | TSDEV/TSDEV                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER0/USER0                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER2/USER2                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER4/USER4                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER6/USER6                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER8/USER8                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | VRR1/VRR1                                                    |
| Oracle                   | Web DB                                | HTTP               | webdb/webdb                                                  |
| Oracle                   | 7 or later                            |                    | Scott/Tiger                                                  |
| Oracle                   | 7 or later                            |                    | system/manager                                               |
| Oracle                   | 8i                                    |                    | internal/oracle                                              |
| Oracle                   | Finacial Package                      | SAP                | SAPR3/SAP                                                    |
| Oracle                   | Oracle RDBMS                          | Multi              | ADAMS/WOOD                                                   |
| Oracle                   | Oracle RDBMS                          | Multi              | APPS/APPS                                                    |
| Oracle                   | Oracle RDBMS                          | Multi              | AQUSER/AQUSER                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | AURORA@/INVALID                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | CATALOG/CATALOG                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | CDEMOCOR/CDEMOCOR                                            |
| Oracle                   | Oracle RDBMS                          | Multi              | CDEMOUCB/CDEMOUCB                                            |
| Oracle                   | Oracle RDBMS                          | Multi              | COMPANY/COMPANY                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | CTXSYS/CTXSYS                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | DBSNMP/DBSNMP                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | DEMO8/DEMO8                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | EVENT/EVENT                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | FND/FND                                                      |
| Oracle                   | Oracle RDBMS                          | Multi              | GPLD/GPLD                                                    |
| Oracle                   | Oracle RDBMS                          | Multi              | MDSYS/MDSYS                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | MILLER/MILLER                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | MODTEST/YES                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | MTYSYS/MTYSYS                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | (none)/(none)                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | NAMES/NAMES                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | ORDPLUGINS/ORDPLUGINS                                        |
| Oracle                   | Oracle RDBMS                          | Multi              | OUTLN/OUTLN                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | POWERCARTUSER/POWERCARTUSER                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | PUBSUB/PUBSUB                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | RMAIL/RMAIL                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | SAMPLE/SAMPLE                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | SECDEMO/SECDEMO                                              |
| Oracle                   | Oracle RDBMS                          | Multi              | SYSADM/SYSADM                                                |
| Oracle                   | Oracle RDBMS                          | Multi              | SYSTEM/MANAGER                                               |
| Oracle                   | Oracle RDBMS                          | Multi              | TSDEV/TSDEV                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER0/USER0                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER2/USER2                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER4/USER4                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER6/USER6                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | USER8/USER8                                                  |
| Oracle                   | Oracle RDBMS                          | Multi              | VRR1/VRR1                                                    |
| Oracle                   | Web DB                                | HTTP               | webdb/webdb                                                  |
| ORiNOCO                  | Access Server                         | Telnet             | (none)/orinoco                                               |
| Osicom                   | JETXPrint                             | Telnet             | sysadm/sysadm                                                |
| Osicom                   | JETXPrint                             | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETCommuter Remote                    | Telnet             | debug/d.e.b.u.g                                              |
| Osicom                   | NETCommuter Remote                    | Telnet             | guest/guest                                                  |
| Osicom                   | NETCommuter Remote                    | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | debug/d.e.b.u.g                                              |
| Osicom                   | NETPrint                              | Telnet             | debug/d.e.b.u.g                                              |
| Osicom                   | NETPrint                              | Telnet             | echo/echo                                                    |
| Osicom                   | NETPrint                              | Telnet             | echo/echo                                                    |
| Osicom                   | NETPrint                              | Telnet             | echo/echo                                                    |
| Osicom                   | NETPrint                              | Telnet             | guest/guest                                                  |
| Osicom                   | NETPrint                              | Telnet             | guest/guest                                                  |
| Osicom                   | NETPrint                              | Telnet             | guest/guest                                                  |
| Osicom                   | NETPrint                              | Telnet             | Manager/Manager                                              |
| Osicom                   | NETPrint                              | Telnet             | Manager/Manager                                              |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | NETPrint                              | Telnet             | sysadm/sysadm                                                |
| Osicom                   | Osicom(Datacom)                       |                    | sysadm/sysadm                                                |
| Otenet                   | otenet                                | Telnet             | (none)/(none)                                                |
| Packeteer                | Packetshaper                          | Console            | N/A/touchpwd=                                                |
| Panasonic                | kx-td816                              |                    | none/1234                                                    |
| Pandatel                 | EMUX                                  |                    | admin/admin                                                  |
| Patton                   | RAS                                   |                    | monitor/monitor                                              |
| PentaSafe                | VigilEnt Security                     | VigilEnt           | PSEAdmin/$secure$                                            |
| Philips                  | Praesideo PA System                   | Multi              | admin/admin                                                  |
| Phoenix                  | 4                                     | Multi              | (none)/admin                                                 |
| Phoenix                  | bios                                  | Multi              | (none)/(none)                                                |
| Phoenix                  | dell                                  | Multi              | (none)/admin                                                 |
| PHPReactor               | PHPReactor                            | HTTP               | core/phpreactor                                              |
| phpTest                  | phpTest                               | HTTP               | admin/1234                                                   |
| PingTel                  | Xpressa                               |                    | admin/(none)                                                 |
| PlainTree                | Waveswitch 100                        |                    | (none)/default.password                                      |
| Planet                   | WAP-1900/1950/2000                    | Multi              | (none)/default                                               |
| Pollsafe                 | Pollsafe                              | MODEM              | SMDR/SECONDARY                                               |
| Polycom                  | Viewstation                           | Telnet             | administrator/(none)                                         |
| Prime                    | PrimeOS                               | Multi              | dos/dos                                                      |
| Prime                    | PrimeOS                               | Multi              | guest/guest                                                  |
| Prime                    | PrimeOS                               | Multi              | guest1/guest                                                 |
| Prime                    | PrimeOS                               | Multi              | maint/maint                                                  |
| Prime                    | PrimeOS                               | Multi              | netlink/netlink                                              |
| Prime                    | PrimeOS                               | Multi              | prime/primeos                                                |
| Prime                    | PrimeOS                               | Multi              | primenet/primeos                                             |
| Prime                    | PrimeOS                               | Multi              | primeos/primeos                                              |
| Prime                    | PrimeOS                               | Multi              | primos_cs/prime                                              |
| Prime                    | PrimeOS                               | Multi              | system/system                                                |
| Prime                    | PrimeOS                               | Multi              | test/test                                                    |
| QDI                      | PC BIOS                               | Console            | (none)/QDI                                                   |
| Quantex                  | PC BIOS                               | Console            | (none)/teX1                                                  |
| Quantum                  | File Servers                          | HTTP               | (none)/(none)                                                |
| Raidzone                 | raid arrays                           |                    | (none)/raidzone                                              |
| RapidStream              | RapidStream                           | Multi              | rsadmin/(null)                                               |
| Raritan                  | KVM Switches                          |                    | admin/raritan                                                |
| realtek                  | 8139                                  |                    | (none)/(none)                                                |
| Reda                     |                                       | HTTP               | (none)/(none)                                                |
| Redemo                   | da                                    | HTTP               | admin/(none)                                                 |
| RedHat                   | Piranha                               | Console            | (none)/Q                                                     |
| RedHat                   | Redhat 6.2                            | HTTP               | piranha/piranha                                              |
| Remedy                   | Any                                   |                    | Demo/(none)                                                  |
| Remedy                   | Remedy                                | Multi              | demos/(none)                                                 |
| Replicom                 | ProxyView                             | NetBIOS            | Administrator/Pvremote                                       |
| Research                 | PC BIOS                               | Console            | (none)/Col2ogro2                                             |
| Research                 | PC BIOS                               | Console            | (none)/Col2ogro2                                             |
| Resumix                  | Resumix                               | N/A                | root/resumix                                                 |
| Ricoh                    | Aficio                                | HTTP               | sysadmin/password                                            |
| Rizen                    | WebGUI                                |                    | Admin/123qwe                                                 |
| RM                       | RM Connect                            | Multi              | admin/rmnetlm                                                |
| RM                       | RM Connect                            | Multi              | adminstrator/changeme                                        |
| RM                       | RM Connect                            | Multi              | deskman/changeme                                             |
| RM                       | RM Connect                            | Multi              | deskres/password                                             |
| RM                       | RM Connect                            | Multi              | replicator/replicator                                        |
| RM                       | RM Connect                            | Multi              | setup/changeme                                               |
| RM                       | RM Connect                            | Multi              | temp1/password                                               |
| RM                       | RM Connect                            | Multi              | topicnorm/password                                           |
| RM                       | Server BIOS                           | Console            | (none)/RM                                                    |
| Rodopi                   | Rodopi billing software               |                    | rodopi/rodopi                                                |
| ROLM                     | phones/phone mail                     |                    | (none)/111#                                                  |
| Roxio                    | Aesy cd                               | Multi              | (none)/(none)                                                |
| S2400                    | Toshiba                               | HTTP               | Administrator/admin                                          |
| Samba                    | SWAT Package                          |                    | Any Local User/Local User password                           |
| Samsung                  | inforanger                            | Multi              | (none)/(none)                                                |
| SAP                      | SAP                                   | SAP                | DDIC/19920706                                                |
| SAP                      | SAP                                   | SAP                | SAP*/PASS                                                    |
| SAP                      | SAP                                   | SAP                | SAPCPIC/ADMIN                                                |
| schoolgirl               | member                                |                    | ich/hci                                                      |
| Securicor3NET            | Cezzanne                              |                    | manager/friend                                               |
| Securicor3NET            | Money                                 |                    | manager/friend                                               |
| security.org             | lockpicking                           | Multi              | admin/(none)                                                 |
| Semaphore                | PICK O/S                              |                    | DESQUETOP/(none)                                             |
| Semaphore                | PICK O/S                              |                    | DSA/(none)                                                   |
| SGI                      | all                                   |                    | root/(none)                                                  |
| SGI                      | IRIX                                  |                    | EZsetup/(none)                                               |
| SGI                      | IRIX                                  |                    | demos/(none by default)                                      |
| Shina                    | LANRover                              |                    | root/(none)                                                  |
| Shiva                    | AccessPort                            |                    | hello/hello                                                  |
| Shiva                    | Integrator                            | Multi              | admin/hello                                                  |
| Shuttle                  | PC BIOS                               |                    | (none)/Spacve                                                |
| Siemens                  | Hicom 100E PBX                        |                    | 31994/31994                                                  |
| Siemens                  | PhoneMail                             |                    | poll/poll                                                    |
| Siemens                  | PhoneMail                             |                    | sysadmin/sysadmin                                            |
| Siemens                  | PhoneMail                             |                    | system/field                                                 |
| Siemens                  | ROLM PBX                              |                    | admin/pwp                                                    |
| Siemens                  | ROLM PBX                              |                    | op/op                                                        |
| Siemens                  | ROLM PBX                              |                    | su/super                                                     |
| Siemens                  | Hicom 100E PBX                        |                    | 31994/31994                                                  |
| Siemens                  | PhoneMail                             |                    | poll/poll                                                    |
| Siemens                  | PhoneMail                             |                    | sysadmin/sysadmin                                            |
| Siemens                  | PhoneMail                             |                    | system/field                                                 |
| Siemens                  | ROLM PBX                              |                    | admin/pwp                                                    |
| Siemens                  | ROLM PBX                              |                    | op/op                                                        |
| Siemens                  | ROLM PBX                              |                    | su/super                                                     |
| Siips                    | Trojan                                | Multi              | Administrator/ganteng                                        |
| sitara                   | qosworks                              | Console            | root/(none)                                                  |
| Sitecom                  | WL-108                                |                    | admin/password                                               |
| SmartSwitch              | Router 250 ssr2500                    | Multi              | admin/(none)                                                 |
| SMC                      | Barricade                             |                    | (none)/admin                                                 |
| SMC                      | Router                                | HTTP               | admin/admin                                                  |
| soho                     | nbg800                                |                    | admin/1234                                                   |
| SonicWALL                | ALL                                   | HTTP               | admin/password                                               |
| Speedstream              | 5861 SMT Router                       | Multi              | admin/admin                                                  |
| Speedstream              | DSL                                   | Multi              | admin/admin                                                  |
| SpeedXess                | HASE-120                              | Multi              | (none)/speedxess                                             |
| Spike                    | CPE                                   | Console            | enable/(none)                                                |
| Ssangyoung               | SR2501                                |                    | (none)/2501                                                  |
| Sun                      | –                                     |                    | (none)/(none)                                                |
| Sun                      | JavaWebServer                         | AdminSrv           | admin/admin                                                  |
| Sun                      | SunScreen                             | TCP 3852           | admin/admin                                                  |
| SuperMicro               | PC BIOS                               | Console            | (none)/ksdjfg934t                                            |
| surecom                  | ep3501/3506                           |                    | admin/surecom                                                |
| Sybase                   | Adaptive Server                       | Multi              | sa/(none)                                                    |
| Sybase                   | Adaptive Server                       | Multi              | sa/(none)                                                    |
| Symantec                 | NAV CORP / ALL                        | HTTP               | admin/symantec                                               |
| Symantec                 | Norton Antivirus                      | Console            | (none)/admin                                                 |
| Symantec                 | pcanywhere                            | Console            | Administrator/(none)                                         |
| SysKonnect               | 6616                                  |                    | default.password/(none)                                      |
| Tekelec                  | Eagle STP                             |                    | eagle/eagle                                                  |
| Teklogix                 | Accesspoint                           | Multi              | Administrator/(none)                                         |
| Telebit                  | NetBlazer                             |                    | setup/snmp/setup/nopassword                                  |
| Tellabs                  | Titan 5500                            | Multi              | tellabs/tellabs#1                                            |
| Telus                    | Telephony Services                    | Multi              | (created)/telus00                                            |
| Terayon                  | TeraLink                              |                    | admin/nms                                                    |
| Terayon                  | TeraLink 1000                         |                    | user/password                                                |
| Terayon                  | TeraLink Getaway                      |                    | user/password                                                |
| Terayon                  | TeraLink Getaway /                    |                    | user/password                                                |
| TextPortal               | TextPortal                            | HTTP               | god2/12345                                                   |
| Tiara                    | Tiara                                 |                    | tiara/tiaranet                                               |
| Tiara                    | Tiara                                 |                    | tiara/tiaranet                                               |
| Tiny                     | PC BIOS                               | Console            | (none)/Tiny                                                  |
| Titbas                   |                                       |                    | haasadm/lucy99                                               |
| TMC                      | PC BIOS                               | Console            | (none)/BIGO                                                  |
| TopLayer                 | AppSwitch 2500                        |                    | siteadmin/toplayer                                           |
| toshiba                  | 480cdt                                |                    | (none)/(none)                                                |
| Toshiba                  | laptop                                | Multi              | Administrator/(none)                                         |
| Toshiba                  | PC BIOS                               | Console            | (none)/toshy99                                               |
| Toshiba                  | PC BIOS                               | Console            | (none)/Toshiba                                               |
| Toshiba                  | satellite 1800-s204                   | HTTP               | (none)/(none)                                                |
| Toshiba                  | satellite pro 4310                    | Multi              | (none)/(none)                                                |
| Toshiba                  | Tecra 8100                            | Multi              | (none)/admin                                                 |
| TrendMicro               | ISVW (VirusWall)                      |                    | admin/admin                                                  |
| Trintech                 | eAcquirer App/                        |                    | t3admin/Trintech                                             |
| Troy                     | ExtendNet 100zx                       | Multi              | admin/extendnet                                              |
| Tumbleweed               | Message Management                    |                    | sa/(none)                                                    |
| Unex                     | NexIP Routers                         |                    | (none)/password                                              |
| Unisys                   | ClearPath MCP                         | Multi              | ADMINISTRATOR/ADMINISTRATOR                                  |
| Unisys                   | ClearPath MCP                         | Multi              | NAU/NAU                                                      |
| UNIX                     | Generic                               | Multi              | adm/adm                                                      |
| UNIX                     | Generic                               | Multi              | admin/admin                                                  |
| UNIX                     | Generic                               | Multi              | administrator/(none)                                         |
| UNIX                     | Generic                               | Multi              | bbs/bbs                                                      |
| UNIX                     | Generic                               | Multi              | bin/sys                                                      |
| UNIX                     | Generic                               | Multi              | checkfsys/checkfsys                                          |
| UNIX                     | Generic                               | Multi              | checksys/checksys                                            |
| UNIX                     | Generic                               | Multi              | daemon/(none)                                                |
| UNIX                     | Generic                               | Multi              | demo/(none)                                                  |
| UNIX                     | Generic                               | Multi              | demos/(none)                                                 |
| UNIX                     | Generic                               | Multi              | dni/dni                                                      |
| UNIX                     | Generic                               | Multi              | fal/fal                                                      |
| UNIX                     | Generic                               | Multi              | fax/fax                                                      |
| UNIX                     | Generic                               | Multi              | ftp/ftp                                                      |
| UNIX                     | Generic                               | Multi              | games/(none)                                                 |
| UNIX                     | Generic                               | Multi              | gropher/(none)                                               |
| UNIX                     | Generic                               | Multi              | guest/guestgue                                               |
| UNIX                     | Generic                               | Multi              | halt/halt                                                    |
| UNIX                     | Generic                               | Multi              | informix/informix                                            |
| UNIX                     | Generic                               | Multi              | lp/lp                                                        |
| UNIX                     | Generic                               | Multi              | lp/lineprin                                                  |
| UNIX                     | Generic                               | Multi              | lpadm/lpadm                                                  |
| UNIX                     | Generic                               | Multi              | lynx/lynx                                                    |
| UNIX                     | Generic                               | Multi              | mail/(none)                                                  |
| UNIX                     | Generic                               | Multi              | man/man                                                      |
| UNIX                     | Generic                               | Multi              | me/(none)                                                    |
| UNIX                     | Generic                               | Multi              | mountfs/mountfs                                              |
| UNIX                     | Generic                               | Multi              | mountsys/mountsys                                            |
| UNIX                     | Generic                               | Multi              | news/(none)                                                  |
| UNIX                     | Generic                               | Multi              | nobody/nobody                                                |
| UNIX                     | Generic                               | Multi              | operator/operator                                            |
| UNIX                     | Generic                               | Multi              | oracle/(none)                                                |
| UNIX                     | Generic                               | Multi              | postmaster/(none)                                            |
| UNIX                     | Generic                               | Multi              | rje/rje                                                      |
| UNIX                     | Generic                               | Multi              | root/root                                                    |
| UNIX                     | Generic                               | Telnet             | service/smile                                                |
| UNIX                     | Generic                               | Telnet             | setup/N/A                                                    |
| UNIX                     | Generic                               | Multi              | shutdown/(none)                                              |
| UNIX                     | Generic                               | Multi              | sync/(none)                                                  |
| UNIX                     | Generic                               | Multi              | sys/system                                                   |
| UNIX                     | Generic                               | Multi              | sysadm/sysadm                                                |
| UNIX                     | Generic                               | Multi              | sysadmin/sysadmin                                            |
| UNIX                     | Generic                               | Multi              | system_admin/(none)                                          |
| UNIX                     | Generic                               | Multi              | trouble/trouble                                              |
| UNIX                     | Generic                               | Multi              | umountfsys/umountfsys                                        |
| UNIX                     | Generic                               | Multi              | unix/unix                                                    |
| UNIX                     | Generic                               | Multi              | uucp/uucp                                                    |
| UNIX                     | Generic                               | Multi              | web/(none)                                                   |
| UNIX                     | Generic                               | Multi              | webmaster/webmaster                                          |
| UNIX                     | Generic                               | Multi              | www/(none)                                                   |
| UNIX                     | koppp                                 | Telnet             | dream/trocse                                                 |
| Unknown                  | POCSAG Radio Paging                   | Port 8000          | (none)/password                                              |
| Unknown                  | System 88                             | Console            | overseer/overseer                                            |
| USR                      | TOTALswitch                           |                    | none/amber                                                   |
| UTStarcom                | B-NAS, B-RAS                          |                    | dbase/dbase                                                  |
| UTStarcom                | B-NAS, B-RAS                          |                    | guru/*3noguru                                                |
| Verifone                 | Verifone Junior                       |                    | (none)/166816                                                |
| Vertex                   | VERTEX 1501                           |                    | root/vertex25                                                |
| Vobis                    | PC BIOS                               | Console            | (none)/merlin                                                |
| voy                      | –                                     |                    | (none)/(none)                                                |
| VPASP                    | VP-ASP Shopping Cart                  | HTTP               | admin/admin                                                  |
| Watchguard               | Firebox                               | Console            | (none)/wg (touch password)                                   |
| Watchguard               | SOHO and SOHO6                        | FTP                | user/pass                                                    |
| webmail                  | webmail v0.94                         | Multi              | kol/gniffe                                                   |
| Webmin                   | Webmin                                | HTTP               | admin/(none)                                                 |
| WebRamp                  | 410i                                  |                    | wradmin/tracell                                              |
| WebTrends                | Enterprise Reporting                  | HTTP               | Admin/(none)                                                 |
| Win2000                  | Quick Time 4.0                        |                    | (none)/(none)                                                |
| winwork                  | iso sistemi                           | Multi              | operator/(none)                                              |
| WorldClient              | AdminServer                           | HTTP:2001          | WebAdmin/Admin                                               |
| WWWBoard                 | WWWADMIN.PL                           | HTTP               | WebAdmin/WebBoard                                            |
| Wyse                     | Winterm                               | BIOS               | (none)/Fireport                                              |
| Wyse                     | Winterm                               | VNC                | VNC/winterm                                                  |
| Xerox                    | Multi Function                        | Multi              | admin/2222                                                   |
| Xerox                    | Workcentre                            |                    | admin/1111                                                   |
| Xylan                    | OmniStack 1032CF                      |                    | admin/password                                               |
| Xylan                    | Omniswitch                            |                    | admin/switch                                                 |
| Xylan                    | Omniswitch                            | Telnet             | diag/switch                                                  |
| Xyplex                   | MX-16XX                               |                    | setpriv/system                                               |
| Xyplex                   | Routers                               | Port 7000          | (none)/system                                                |
| Xyplex                   | Terminal Server                       | Port 7000          | (none)/system                                                |
| Zcom                     | Wireless                              | SNMP               | root/admin                                                   |
| Zenith                   | PC BIOS                               | Console            | (none)/3098z                                                 |
| ZEOS                     | PC BIOS                               | Console            | (none)/zeosx                                                 |
| Zeus                     | Zeus Admin Server                     | HTTP               | admin/(none)                                                 |
| ZyXEL                    | 641 ADSL                              |                    | (none)/1234                                                  |
| ZTE                      | ZXV10 W300 Rev.                       |                    | admin/admin                                                  |
| ZyXEL                    | Generic Routers                       | Telnet             | (none)/1234                                                  |
| Zyxel                    | ISDN-Router Prestige                  |                    | (none)/1234                                                  |
| ZyXEL                    | Prestige                              | Telnet             | (none)/1234                                                  |
| ZyXEL                    | Prestige 128                          |                    | (none)/1234                                                  |
| zyxel                    | prestige 300 series                   |                    | (none)/1234                                                  |
| 迅捷                     | Fast                                  | HTTP               | admin/admin                                                  |
| 艾玛701g                 | 艾玛701g                              | HTTP               | admin/admin SZIM/SZIM                                        |
| 艾玛701H                 | 艾玛701H                              | HTTP               | admin/epicrouter                                             |
| 实达                     | 实达 2110EHROUTER                     | HTTP               | user/password root/grouter                                   |
| 实达                     | 实达 2110EHROUTER v3.20               | HTTP               | admin/conexant                                               |
| 实达                     | 实达 2110EHROUTER v3.21               | HTTP               | admin/conexant                                               |
| 实达                     | 实达 2110EHROUTER v3.51               | HTTP               | admin/conexant                                               |
| 实达                     | 实达 2110EHROUTER v4.5                | HTTP               | root/grouter                                                 |

设备口令扩展：

```C
华为服务器:root:Huawei12#$
Cisco:cisco:cisco
TP-Link:admin:admin
D-link:admin:admin
Tenda:admin:admin
HUAWEI:admin:admin
Netcore:guest:guest
Fast:admin:admin
PHICOMM:admin:admin
ASUS:admin:admin
艾玛701g:admin:admin/SZIM:SZIM
艾玛701H:admin:epicrouter
实达2110EHROUTER:user:password/root:grouter
神州数码/华硕:adsl:adsl1234
全向:root:root
普天:admin:dare
e-tek:admin:12345
zyxel:anonymous:1234
北电:anonymous:12345
大恒:admin:admin
大唐:admin:1234/user:user
中兴:adsl:adsl831
伊泰克:supervisor:12345
同维DSL699E:root:root
大亚DB102:admin:dare
WST RT1080:root:root
WST ART18CX:admin:conexant/user:assword
全向qxcomm1688:qxcommsuport
全向qxcomm1680:qxcomm1680
实达V3.2:root:root
实达V5.4:root:grouter
泛德:admin:conexant
东信Ea700:空:password
broadmax的hsa300a:broadmax:broadmax
长虹ch-500E:root:root
重庆普天CPADSL03:root:root
台湾突破EA110:usernameSL:pswSL
etek-td的ADSL_T07L006.0:supervisor:12345/使用超级终端的Xmodem方式重写Vxworks.dlf，密码恢复成：12345
GVC的DSL-802E/R3A:admin:epicrouter/user:password
科迈易通km300A-G:root:root
科迈易通km300A-A:rootoradmin:123456
sunrise的SR-DSL-AE:admin:0000
sunrise的DSL-802E_R3A:admin:epicrouter/user:password
UTStar的ut-300R:rootoradmin:utstar
锐捷:admin:ruijie
TP-LINKTD-8800在IE输入192.168.1.1,用户名admin,密码为admin.
合勤zyxel642telnet192.168.1.1密码1234
EcomED-802EG在IE输入192.168.1.1用户名和密码都为root
神州数码6010RA在IE输入192.168.1.1　用户名ADSL密码为ADSL1234
华为SmartAXMT800初始IP是192.168.1.1用户名和密码都为admin
伊泰克http://192.168.1.1用户名：supervisor密码：12345
华硕http://192.168.1.1用户名：adsl密码：adsl1234
阿尔卡特http://192.168.1.1一般没有密码
同维DSL699Ehttp://192.168.1.1用户名：ROOT密码为：ROOT
大亚DB102http://192.168.1.1用户名：admin密码：dare
WST的RT1080http://192.168.0.1username:rootpassword:root
WST的ART18CXhttp://10.0.0.2username:adminpassword:conexant
username:userpassword:password
全向qxcomm1688http://192.168.1.1高端设置密码是：qxcommsuport
全向qxcomm1680http://192.168.1.1用户：qxcomm1680密码:qxcomm1680
实达
实达ADSL2110-EHaddress:192.168.10.1user:adminpwd:starnetadsl
V3.2　rootroot
V5.4　rootgrouter
泛德用户：admin密码：conexant
东信Ea700http://192.168.1.1用户名：空密码：password
broadmax的hsa300ahttp://192.168.0.1username:broadmax
password:broadmax
长虹ch-500Ehttp://192.168.1.1username:rootpassword:root
重庆普天CPADSL03http://192.168.1.1username:rootpassword:root
台湾突破EA110RS232:38400http://192.168.7.1username:SLpsw:SL
etek-td的ADSL_T07L006.0http://192.168.1.1UserName:super ... 
GVC的DSL-802E/R3A
username:userpassword:password
科迈易通km300A-1http://192.168.1.1username:password:password
科迈易通km300A-Ghttp://192.168.1.1username:rootpassword:root
科迈易通km300A-Ausername:rootoradminpassword:123456
sunrise的SR-DSL-AEhttp://192.168.1.1username:adminpassword:0000
sunrise的DSL-802E_R3Ahttp://10.0.0.2username:admin
password:epicrouter
username:userpassword:password
UTStar的ut-300Rhttp://192.168.1.1 username:admin
password:utstar
湖北邮通IP:10.0.0.2 Username:admin Password:epicrouter
亨威NSM500网速通IP:192.168.1.1 Username:root Password:root
艾玛701g192.168.101.1192.168.0.1用户名：admin密码：admin
用户名：SZIM 密码：SZIM
艾玛701H192.168.1.110.0.0.2用户名：admin密码：epicrouter
实达2110EHROUTER 192.168.10.1 用户名：user密码：password
用户名：root密码：grouter
神州数码/华硕：用户名：adsl密码：adsl1234
全向：用户名：root密码：root
普天：用户名：admin密码：dare
e-tek用户名:admin密码:12345
zyxel用户名:anonymous密码:1234
北电用户名:anonymous密码:12345
大恒用户名：admin密码：admin
大唐用户名：admin密码：1234
斯威特用户名：root密码：root
用户名：user密码：user
中兴用户名：adsl密码：adsl831
```

###### 摄像头

| 厂商              | 产品                  | 协议 | 口令                         |
| ----------------- | --------------------- | ---- | ---------------------------- |
| ACTi              | ACTi                  | HTTP | admin/123456 or Admin/123456 |
| American Dynamics | American Dynamics     | HTTP | admin/admin or admin/9999    |
| Arecont Vision    | Arecont Vision        | HTTP | none                         |
| Avigilon          | Avigilon              | HTTP | admin/admin                  |
| Basler            | Basler                | HTTP | admin/admin                  |
| Bosch             | Bosch                 | HTTP | none                         |
| Brickcom          | Brickcom              | HTTP | admin/admin                  |
| Canon             | Canon                 | HTTP | root/camera                  |
| Dahua             | Dahua                 | HTTP | admin/admin                  |
| Digital Watchdog  | Digital Watchdog      | HTTP | admin/admin                  |
| DRS               | DRS                   | HTTP | admin/1234                   |
| DVTel             | DVTel                 | HTTP | Admin/1234                   |
| DynaColor         | DynaColor             | HTTP | Admin/1234                   |
| FLIR              | FLIR                  | HTTP | admin/fliradmin              |
| Foscam            | Foscam                | HTTP | admin/                       |
| GeoVision         | GeoVision             | HTTP | admin/admin                  |
| Grandstream       | Grandstream           | HTTP | admin/admin                  |
| Hikvision         | Hikvision             | HTTP | admin/12345                  |
| Honeywell         | Honeywell             | HTTP | admin/1234                   |
| IQinVision        | IQinVision            | HTTP | root/system                  |
| IPX-DDK           | IPX-DDK               | HTTP | root/admin or root/Admin\|   |
| JVC               | JVC                   | HTTP | admin/jvc                    |
| March             | March Networks        | HTTP | admin/                       |
| Mobotix           | Mobotix               | HTTP | admin/meinsm                 |
| Panasonic         | Panasonic             | HTTP | admin/12345                  |
| Pelco Sarix       | Pelco Sarix           | HTTP | admin/admin                  |
| Pixord            | Pixord                | HTTP | admin/admin                  |
| Samsung           | Samsung Electronics   | HTTP | root/root or admin/4321      |
| Samsung           | Samsung Techwin (old) | HTTP | admin/1111111                |
| Samsung           | Samsung (new)         | HTTP | admin/4321                   |
| Sanyo             | Sanyo                 | HTTP | admin/admin                  |
| Scallop           | Scallop               | HTTP | admin/password               |
| Sentry360         | Sentry360 (mini)      | HTTP | admin/1234                   |
| Sentry360         | Sentry360 (pro)       | HTTP | none                         |
| Sony              | Sony                  | HTTP | admin/admin                  |
| Speco             | Speco                 | HTTP | admin/1234                   |
| Stardot           | Stardot               | HTTP | admin/admin                  |
| Starvedia         | Starvedia             | HTTP | admin/                       |
| Trendnet          | Trendnet              | HTTP | admin/admin                  |
| Toshiba           | Toshiba               | HTTP | root/ikwd                    |
| VideoIQ           | VideoIQ               | HTTP | supervisor/supervisor        |
| Vivotek           | Vivotek               | HTTP | root/                        |
| Ubiquiti          | Ubiquiti              | HTTP | ubnt/ubnt                    |
| Wodsee            | Wodsee                | HTTP | admin/                       |

##### 安全产品

|                     |                                        |                                                              |                                                 |
| ------------------- | -------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------- |
| 厂商                | 产品                                   | 口令                                                         | FOFA Pro 查询语法                               |
| 深信服              | 深信服产品                             | sangfor/sangfor sangfor/sangfor@2018 sangfor/sangfor@2019 admin/admin | app="深信服-公司产品"                           |
| 深信服              | 深信服科技 AD                          | /dlanrecover                                                 |                                                 |
| 深信服              | 深信服负载均衡 AD 3.6                  | admin/admin                                                  |                                                 |
| 深信服              | 深信服 AD3.9                           | admin/admin                                                  |                                                 |
| 深信服              | 深信服 WAC ( WNS V2.6)                 | admin/admin                                                  |                                                 |
| 深信服              | 深信服 VPN                             | Admin/Admin                                                  | app="深信服-SSL-VPN"                            |
| 深信服              | 深信服 ipsec-VPN (SSL 5.5)             | Admin/Admin                                                  | app="深信服-IPSec-VPN"                          |
| 深信服              | 深信服 AC 6.0                          | admin/admin                                                  |                                                 |
| 深信服              | SANGFOR 防火墙                         | admin/sangfor                                                | app="深信服-防火墙类产品"                       |
| 深信服              | 深信服 AF（NGAF V2.2）                 | admin/sangfor                                                |                                                 |
| 深信服              | 深信服 NGAF下一代应用防火墙(NGAF V4.3) | admin/admin                                                   |                                                 |
| 深信服              | 深信服上网行为管理设备数据中心         | Admin/空                                                     | app="SANGFOR上网行为管理"                       |
| 深信服              | SANGFOR_AD_v5.1                        | admin/admin                                                  |                                                 |
| 深信服              | 深信服防火墙                           | admin/admin                                                  | app="深信服-防火墙类产品"                       |
| 启明星辰            | 启明星辰                               | admin/admin@123 admin/bane@7766                              |                                                 |
| 启明星辰            | 天阗入侵检测与管理系统 V7.0            | Admin/venus70 Audit/venus70 adm/venus60                      | body="天阗入侵检测与管理系统V7.0"               |
| 启明星辰            | 天阗入侵检测与管理系统 V6.0            | Admin/venus70 Audit/venus70 adm/venus60                      |                                                 |
| 启明星辰            | 天玥网络安全审计系统                   | Admin/cyberaudit                                             | app="启明星辰-天玥网络安全审计"                 |
| 启明星辰            | 天清汉马 USG 防火墙                    | admin/venus.fw Audit/venus.audit useradmin/venus.user        | app="启明星辰-天清汉马USG"                      |
| 启明星辰            | 启明泰合信息安全运营中心               | sysadmin/venus.sysadmin useradmin/venus.useradmin auditor/venus | app="启明星辰-泰合信息安全运营中心"             |
| 网御星云            | 网御 WAF 集中控制中心（V3.0R5.0）      | admin/leadsec.waf audit/leadsec.waf adm/leadsec.waf          | app="网御WAF"                                   |
| 网御星云            | 网御漏洞扫描系统                       | leadsec/leadsec                                              |                                                 |
| 网御星云            | 网御入侵检测系统 V3.2.72.0             | adm/leadsec32 admin/leadsec32                                | app="网御入侵防护系统"                          |
| 联想网御            | 联想网御                               | administrator/administrator admin/leadsec@7766 admin/administrator admin/bane@7766 |                                                 |
| 联想网御            | 网御事件服务器                         | admin/admin123                                               |                                                 |
| 联想网御            | 联想网御防火墙 PowerV                  | administrator/administrator  admin/administrator admin/leadsec@7766 admin/bane@7766 |                                                 |
| 联想网御            | 联想网御入侵检测系统                   | lenovo/default                                               | app="网御入侵防护系统"                          |
| 联想网御            | 联想网御入侵检测系统 IDS               | root/111111 admin/admin123                                   | app="网御入侵防护系统"                          |
| 科来                | 科来网络回溯分析系统                   | csadmin/colasoft                                             | app="科来网络回溯分析系统服务器"                |
| 中控                | 中控考勤机 web3.0                      | administrator/123456                                         | app="Zkteco-门禁管理系统"                       |
| H3C                 | H3C iMC                                | admin/admin                                                  | app="H3C-iMC"                                   |
| H3C                 | H3C SecPath系列                        | admin/admin                                                  | app="H3C-SecPath防火墙"                         |
| H3C                 | H3C S5120-SI                           | test/123                                                     | app="H3C-S5120"                                 |
| H3C                 | H3C 智能管理中心                       | admin/admin                                                  | app="H3C-iMC智能管理中心"                       |
| H3C                 | H3C ER3100                             | admin/adminer3100                                            | app="H3C-ER3100"                                |
| H3C                 | H3C ER3200                             | admin/adminer3200                                            | app="H3C-ER3200"                                |
| H3C                 | H3C ER3260                             | admin/adminer3260                                            | app="H3C-ER3260"                                |
| H3C                 | H3CMSR20                               | admin/admin                                                  | app="H3C-Series-Router-MSR20-20"                |
| H3C                 | H3C                                    | admin/adminer admin/admin admin/h3capadmin h3c/h3c           | app="H3C公司产品"                               |
| 奇安信              | 360 天擎                               | admin/admin                                                  | app="360天擎"                                   |
| 网神                | 网神                                   | admin/firewall firewall/firewall                             | body="账号只能是admin或者audit"                 |
| 奇安信/网神         | 网神防火墙                             | firewall/firewall                                            | app="网神-防火墙"                               |
| 奇安信/网神         | 网神 SecFox 运维安全管理与审计系统     | admin/!1fw@2soc#3vpn                                         | app="网神SecFox安全审计系统"                    |
| 奇安信/网神         | 网神防火墙GE1口                        | admin/firewall                                               |                                                 |
| 天融信              | 网络卫士入侵检测系统                   | admin/talent                                                 | app="天融信-入侵防御系统TopIDP"                 |
| 天融信              | 天融信防火墙                           | superman/talent superman/talent!23                           | app="天融信-防火墙"                             |
| 天融信              | 天融信防火墙 NGFW4000                  | superman/talent                                              | app="天融信-NGFW4000"                           |
| 天融信              | 天融信数据库审计系统                   | superman/telent                                              | app="天融信-网络审计系统"                       |
| 天融信              | 天融信 TopAudit 日志审计系统           | superman/talent                                              | app="天融信-TopAudit"                           |
| 天融信              | 天融信 vpn                             | test/123456                                                  | app="天融信-VPN"                                |
| 海峡信息            | 黑盾防火墙                             | admin/admin rule/abc123 audit/abc123                         | body="黑盾防火墙"                               |
| 华为                | Huawei                                 | admin/Admin@123                                              | app="华为-公司产品"                             |
| 华为                | 华为防火墙                             | telnetuser/telnetpwd ftpuser/ftppwd                          | app="华为-USG防火墙"                            |
| 华为                | 华为VPN                                | root/mduadmin                                                |                                                 |
| 方正                | 方正防火墙                             | admin/admin administrator/administrator                      | app="方正-安全网关"                             |
| 飞塔                | 飞塔防火墙                             | admin/空                                                     |                                                 |
| 欧非信息（juniper） | Juniper_SSG__5防火墙                   | netscreen/netscreen                                          |                                                 |
| 中新金盾            | 中新金盾硬件防火墙                     | admin/123                                                    | app="中新金盾-FireWall"                         |
| 冠群金辰            | kill 防火墙（冠群金辰）                | admin/sys123                                                 |                                                 |
| 阿姆瑞特            | 阿姆瑞特防火墙                         | admin/manager                                                |                                                 |
| 山石网科            | 山石网科                               | hillstone/hillstone                                          | app="山石网科-流量管理"                         |
| 山石网科            | Hillstone 安全审计平台                 | hillstone/hillstone                                          | app="Hillstone安全审计平台"                     |
| 绿盟                | 绿盟安全审计系统                       | weboper/weboper webaudit/webaudit conadmin/conadmin admin/admin shell/shell | app="绿盟日志数据安全性分析系统"                |
| 绿盟                | 绿盟IPS                                | weboper/weboper                                              | app="绿盟-WAF"                                  |
| 思福迪              | LogBase 日志管理综合审计系统           | admin/safetybase                                             | app="思福迪-LOGBASE日志管理综合审计系统"        |
| 网康科技            | 网康日志中心                           | ns25000/ns25000                                              | app="网康-日志分析"                             |
| 中科新业            | 网络安全审计系统（中科新业）           | admin/123456                                                 |                                                 |
| 安恒信息            | 明御 WEB 应用防火墙                    | admin/admin admin/adminadmin                                 | app="明御WEB应用防火墙"                         |
| 安恒信息            | 明御攻防实验室平台                     | root/123456                                                  |                                                 |
| 安恒信息            | 明御安全网关                           | admin/adminadmin                                             | body="/webui/images/basic/login/logo_DBApp.png" |
| 安恒信息            | 明御运维审计与册风险控制系统           | admin/1q2w3e system/1q2w3e4r auditor/1q2w3e4r operator/1q2w3e4r | app="明御-运维审计与风险控制系统"               |
| 安恒信息            | 明御网站卫士                           | sysmanager/sysmanager888                                     | app="安恒信息-明御WEB应用防火墙"                |
| 安恒信息            | 明御防火墙                             | admin/adminadmin                                             | app="安恒-防火墙"                               |
| 亿中邮信息          | 亿邮邮件网关                           | eyouuser/eyouuser eyougw/admin@(eyou) admin/+-ccccc admin/cyouadmin | app="亿邮-反垃圾邮件网关"                       |
| Websense            | Websense 邮件安全网关                  | administrator/admin                                          | app="Websense-Email-Security-Gateway"           |
| 梭子鱼              | 梭子鱼邮件存储网关                     | admin/admin                                                  | app="梭子鱼垃圾邮件防火墙"                      |
| 华为                | 华为USG防火墙                          | admin/Admin@123 audit-admin/Admin@123 api-admin/Admin@123    | app="华为-USG防火墙"                            |
| 思科                | 思科                                   | admin/cisco                                                  | app="Cisco-公司产品"                            |
|                     |                                        |                                                              |                                                 |
| 科达                | 科达网络键盘控制台                     | admin/kedacom123                                             | title="网络键盘控制台"                          |
| 移动                | 云视讯C21\C11\C31                      | admin/Starnet@0591                                           | body="userName.png"&&body="verifyCode.png"      |
| 星网锐捷数字标牌    | 星网锐捷数字标牌                       | root/root1234                                                | body="DMB-"&&body="anonymousUser"               |

##### 应用产品

###### 堡垒机

| 厂商       | 产品                                                   | 口令        | FOFA Pro查询语法         |
| ---------- | ------------------------------------------------------ | ----------- | ------------------------ |
| Jumpserver | [JumpServer](https://github.com/jumpserver/jumpserver) | admin/admin | `app="Jumpserver堡垒机"` |

###### 数据库

|                      |                                                              |                                                              |                           |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------- |
| 厂商                 | 产品                                                         | 口令                                                         | FOFA Pro 查询语法         |
| Oracle               | [Oracle](https://www.oracle.com/cn/database/)                | internal/oracle <br />system/manager sys/change_on_install <br />scott/tiger <br />scott/scott | `protocol="oracle"`       |
| Oracle               | [MySQL](https://www.mysql.com/)                              | root/空 root/root                                            | `protocol="mysql"`        |
| Microsoft            | [Microsoft SQL Server](https://www.microsoft.com/en-au/sql-server) | sa/sa                                                        | `protocol="mssql"`        |
| PostgreSQL           | [PostgreSQL](https://www.postgresql.org/)                    | postgres/空 <br />admin/admin                                | `app="PostgreSQL"`        |
| MongoDB              | [MongoDB](http://dream0x01.com/spear-framework/#/www.mongodb.com) | 无                                                           | `app="MongoDb"`           |
| IBM                  | [IBM Db2](http://dream0x01.com/spear-framework/#/)           | db2admin/db2admin <br />db2inst1/ibmdb2 <br />db2as/ibmdb2 <br />db2fenc1/ibmdb2 | `app="DB2数据库"`         |
| Elastic              | [Elasticsearch](https://www.elastic.co/cn/elasticsearch/)    | 无                                                           | `app="Elasticsearch"`     |
| Salvatore Sanfilippo | [Redis](https://redis.io/)                                   | 无                                                           | `app="redis"`             |
| SQLite               | [SQLite](https://www.sqlite.org/)                            | 无                                                           |                           |
| Apache               | [Cassandra](https://cassandra.apache.org/)                   | 无                                                           | `protocol="cassandra"`    |
| Microsoft            | [Access](https://www.microsoft.com/en-us/microsoft-365/access) | 无                                                           |                           |
| MariaDB              | [MariaDB](http://dream0x01.com/spear-framework/#/)           | root/空 root/root                                            | `protocol="mysql"`        |
| Splunk Inc.          | [Splunk](https://www.splunk.com/)                            | admin/changeme                                               | `app="Splunk"`            |
| Apache               | [Hive](https://hive.apache.org/)                             | root/mine                                                    |                           |
| Teradata             | [Teradata](https://www.teradata.com/)                        | dbc/dbc                                                      | `app="Teradata-公司产品"` |
| Apache               | [Solr](https://lucene.apache.org/solr/)                      | 无                                                           | `app="Solr"`              |

###### 中间件

|           |                                                     |                                                    |                            |
| --------- | --------------------------------------------------- | -------------------------------------------------- | -------------------------- |
| 厂商       | 产品                                                | 口令                                                | FOFA Pro查询语法             |
| Apache    | Tomcat                                              | admin/空                                            | `app="Tomcat默认页面"`     |
| IBM       | WebSpher                                            | admin/admin                                        |                            |
| Jboss     | Jboss                                               | admin/admin                                        |                            |
| Apache    | Axis2                                               | admin/admin                                        |                            |
| F5        | BIG-IP                                              | root/default <br />admin/default <br />admin/admin | `title="BIG-IP®- Redirect" |
| portainer | [portainer](https://github.com/portainer/portainer) | admin/tryportainer                                 | `app="Portainer"`          |

##### Web应用
|            |                                                    |                                                    |                               
| ---------  | --------------------------------------------------- | -------------------------------------------------- |
| 厂商       | 产品                                                | 口令                                                 | 
| Zabbix    | Zabbix                                              | Admin/12345                                         | 


##### IOT产品

|            |               |      |                               |
| ---------- | ------------- | ---- | ----------------------------- |
| 厂商       | 产品          | 协议 | 口令                          |
| Schneider  | M340          | FTP  | sysdiag/factorycast@schneider |
| Schneider  | M340          | Web  | USER/USER                     |
| Schneider  | Premium       | FTP  | sysdiag/factorycast@schneider |
| Schneider  | Premium       | WEB  | USER/USER                     |
| Siemens    | S7-1200       | Web  | admin                         |
| GarrettCom | Magnum Switch | Web  | manager/manager               |

### 在线查询

~~~c
#路由密码
https://www.routerpasswords.com/
https://portforward.com/router-password
https://www.cleancss.com/router-default/
https://toolmao.com/baiduapp/routerpwd/

#默认密码
https://cirt.net/passwords
https://datarecovery.com/rd/default-passwords/
~~~

### 参考链接

https://db-engines.com/en/ranking

http://dream0x01.com/spear-framework
