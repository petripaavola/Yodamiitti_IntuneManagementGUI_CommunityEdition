# Yodamiitti Intune Management GUI Community Edition v1.0
Advanced Powershell based GUI for Intune management

* Update: New version 2.0 is work in progress. It will have threading support so that enables new possibilities like separate windows for device details etc...

### Devices view
![Yodamiitti_IntuneManagementGUI_CommunityEdition_Devices.png](https://www.petripaavola.fi/Yodamiitti_IntuneManagementGUI_CommunityEdition_Devices.png)

### Copy device/app information as JSON
![Yodamiitti_IntuneManagementGUI_CommunityEdition_rightclick_copy_json.png](https://www.petripaavola.fi/Yodamiitti_IntuneManagementGUI_CommunityEdition_rightclick_copy_json.png)

### Search Devices in DeviceCategory (categories are shown in dropdown box)
![Yodamiitti_IntuneManagementGUI_CommunityEdition_Devices_search_by_devicecategory.png](https://www.petripaavola.fi/Yodamiitti_IntuneManagementGUI_CommunityEdition_Devices_search_by_devicecategory.png)

### Apps view
![Yodamiitti_IntuneManagementGUI_CommunityEdition_Apps_.png](https://www.petripaavola.fi/Yodamiitti_IntuneManagementGUI_CommunityEdition_Apps_.png)

### Powershell scripts view
![Yodamiitti_IntuneManagementGUI_CommunityEdition_Powershell_.png](https://www.petripaavola.fi/Yodamiitti_IntuneManagementGUI_CommunityEdition_Powershell_.png)

## Prerequisities
Install Intune Powershell
SDK https://github.com/Microsoft/Intune-PowerShell-SDK

## What & Why
This tool is built to help Intune admins to do some daily tasks easier and quicker than in Intune Web UI

This started as Intune Powershell tips & tricks project and then escalated a little bit. Code is in many places still ad-hoc style but it works ;)

## Highlights
* Find Devices and Apps easily with different search filters - eg. show only Windows, iOS or Android related Devices/Apps
* Search by any information found from Intune (Graph API)
* Copy Device/App full information in JSON format to clipboard (with right-click)
* Sort by any column
* Do device actions to multiple Devices at once (sync/reboot/owner/deviceCategory/...)
* Do multiple App assignments to selected AAD Group
* Show Apps which have assignments to selected AAD Group
* Show Powershell scripts content
## Backlog
* Change script to multi threading model (work in progress)
* Confirmation popup for actions
* Users and Groups TAB
* Profiles TAB
* Autopilot TAB
* Search devices where user is logged on
* Profile examples for Onedrive for Business and Chrome
* more custom search filters examples
* rewrite everything, document everything - timeframe eternity :)

## Disclaimer
This tool is provided "AS IS" without any warranties so please evaluate it in test environment before production use. It is provided as Powershell script so there is no closed code and you can evaluate everything it does. Trust is important when using Administrative user rights and tools in your production environment. I use this tool daily in production environments I manage myself.
