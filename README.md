## RSAT (Remote Server Administration Tools)

RSAT allows IT administrators to remotely administer Windows Server roles and features from a computer running Windows 10 or Windows 7 Service Pack 1.

## Introduction
RSAT cannot be installed on computers running Home or Standard editions of Windows. It is only supported on Professional or Enterprise editions of the Windows client operating system. Unless explicitly stated on the download page that RSAT applies to a beta, preview, or other prerelease version of Windows, you must be using a full (RTM) release of the Windows operating system to install and use RSAT. Some users have attempted to manually modify or bypass restrictions to install RSAT on unsupported Windows editions or releases. Doing so violates the Windows end-user license agreement.

Installing RSAT is comparable to installing Adminpak.msi on Windows 2000 or Windows XP client computers. However, one key difference exists: in Windows 7, the tools are not immediately available after downloading and installing RSAT. You must enable the tools you wish to use through Control Panel. To enable them, go to **Start** > **Control Panel** > **Programs and Features**, and then choose **Turn Windows features on or off**.

In RSAT releases for Windows 10, all tools are enabled by default once again. You can still access **Turn Windows features on or off** to disable any tools you do not plan to use.

For RSAT on Windows 7, you need to enable the tools corresponding to the roles and features you intend to manage after running the downloaded installer.

If you need to install management tools in Windows Server 2012 R2 for specific roles or features running on remote servers, no additional software is required. Launch the Add Roles and Features Wizard in Windows Server 2012 R2 or later. Then, on the **Select Features** page, expand **Remote Server Administration Tools** and choose the tools you want to install. Complete the wizard to install the selected management tools.

## RSAT for Windows 10, version 1809 or later versions

> **Note**  
> You cannot use the Turn Windows features on and off dialog from the Control Panel.

Installing RSAT Tools for Windows 10 version 1809 and later differs slightly from earlier versions. RSAT is now included as part of the Operating System and can be installed through **Optional Features**.

To enable the tools, go to **Start** > **Settings** > **Apps** (if you are using Windows 10, version 22H2 or later, select **System** instead), and then choose **Optional features**. Next, select the **Add a feature** panel and type *Remote* in the search bar.
