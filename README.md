# Disabling Windows Copilot - Widnows 10/11 and MS Edge



### How to disable Windows Copilot using Group Policy for both Windows 10 and 11 (Taskbar and Windows Search):
References: https://learn.microsoft.com/en-us/windows/client-management/manage-windows-copilot

1. To disable Windows Copilot using Group Policy for both Windows 10 and 11: Create a new or modify an existing user based GPO that applies to all of your users in your domain.  
  User Configuration > Administrative Templates > Windows Components > Windows Copilot > Turn off Windows Copilot : Set this to Enabled
  ![image](https://github.com/msab05/Disabling-Windows-Copilot/assets/61631832/53be7b05-af24-4fbc-8393-776732e29406)
*If you do not see this GPO, import the latest ADMX files. The process for importing Windows 10/11 ADMX files outlined here: https://www.prajwaldesai.com/download-windows-11-administrative-templates/




### How to disable Windows Copilot in MS Edge for both Windows 10 and 11 using Group Policy:
Currenlty the only way to disable Copilot from MS Edge is to remove the Hubs Sidebar. To do this:

1. Create a new or modify an existing computer based GPO that applies to all of your devices in your domain.
Computer Configuration > Administrative Templates > Microsoft Edge > Show Hubs Sidebar : Set this to Disabled
![image](https://github.com/msab05/Disabling-Windows-Copilot/assets/61631832/54682aba-66da-4755-9323-70db440b91b2)
*If you do not see this GPO, import the latest ADMX files. The process for importing MS Edge ADMX files outlined here: https://www.prajwaldesai.com/admx-templates-for-microsoft-edge/
