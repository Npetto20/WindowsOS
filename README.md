
<h2 align="center"><img width=32px src="https://i.ibb.co/5KpSCNv/win11.png"> Awesome Windows 11 (<a href="https://github.com/awesome-windows11/windows11/releases/tag/3.8.1">v3.8.1</a>)</h2>

First help for setup, tweaks and ISO images

Our mission is to show that it is possible to configure Windows without using third-party programs, just learn a few simple tweakers.
<br>This way you can forget about extraneous cleaning tools with closed source code. All our scripts are written in the standard "PS1" language and you can always check them or change them to suit your needs. 
<br>
No files or programs, just console and commands!

> MORE PROJECTS: https://github.com/awesome-windows11
> <br>
> Site: https://windows12.glitch.me
> <br>
> VK: https://vk.com/flighthub
> <br>
> Telegram: https://t.me/windows11_chat

<h3 align="center"><img width=20px src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Red%20exclamation%20mark/3D/red_exclamation_mark_3d.png"> Important</h3> 

<img width=20px src="https://community.chocolatey.org/content/packageimages/microsoft-windows-terminal.0.2.1831.001.png"> NT/SYSTEM console: https://github.com/gerardog/gsudo
<br>
<img width=20px src="https://store-images.s-microsoft.com/image/apps.33061.13510798887475206.34a5b1cc-aab2-4ec5-ac80-54aecc0eb29a.fb80a0d9-dd99-4cfc-92c3-e937dd0dc5c9?mode=scale&q=90&w=300&h=300&background=%230078d7"> AppInstaller & MSIXbundle (WinGet) https://apps.microsoft.com/store/detail/9NBLGGH4NNS1
<br>
<img width=20px src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Slightly%20smiling%20face/3D/slightly_smiling_face_3d.png"> Microsoft Emoji: https://github.com/microsoft/fluentui-emoji
<br>
https://github.com/farag2/Utilities

[HACK: Password Brute Force](https://github.com/InfosecMatter/Minimalistic-offensive-security-tools)

<h3 align="center"><img width=25px src="https://site-iota-coral.vercel.app/icon/defender.png"></img> Windows Defender</h3>

[Defender Control](https://www.sordum.org/files/downloads.php?st-defender-control)
<br>
https://github.com/swagkarna/Defeat-Defender-V1.2
<br>
https://github.com/AndyFul/ConfigureDefender
<br>
https://github.com/simeononsecurity/Windows-Defender-Hardening
<br>
https://github.com/simeononsecurity/Windows-Defender-Application-Control-Hardening

<h3 align="center"><img width=25px src="https://site-iota-coral.vercel.app/icon/update.png"></img> Windows Update</h3>

https://github.com/DavidXanatos/wumgr
<br>
https://github.com/WereDev/Wu10Man

<h3 align="center"><img width=25px src="https://site-iota-coral.vercel.app/icon/store.png"> Microsoft Store Apps</h3>

https://github.com/Digressive/Remove-MS-Store-Apps
<br>
https://github.com/Sycnex/Windows10Debloater
<br>
https://github.com/Fs00/Win10BloatRemover
<br>
https://github.com/equk/windows
<br>
https://github.com/r33int/Windows10-Postinstall
<br>
https://github.com/simeononsecurity/Windows-Optimize-Harden-Debloat
<br>
https://github.com/simeononsecurity/Windows-Optimize-Debloat
<br>
https://github.com/ChrisTitusTech/winutil


<h3 align="center">🛠 Tweaks (Win11)</h3>

Custom Context Menu: https://github.com/ikas-mc/ContextMenuForWindows11
<br>
Windows Fixer: https://github.com/99natmar99/Windows-11-Fixer
<br>
Old Start Menu: https://github.com/bbmaster123/10SM
<br>
Explorer Patcher (Old TaskBar): https://github.com/valinet/ExplorerPatcher
<br>
https://github.com/undergroundwires/privacy.sexy
<br>
https://github.com/mikeroyal/Windows-11-Guide
<br>
https://github.com/xanderfrangos/twinkle-tray
<br>
Manager context menu: https://nilesoft.org
<br>
<br>
☠ [OUTDATED: Drag And Drop To Taskbar Fix](https://github.com/HerMajestyDrMona/Windows11DragAndDropToTaskbarFix)
<br>
☠ [OUTDATED: Windows Thumbnail Generator Folder](https://github.com/hahagu/WindowsThumbnailGenerator) 



<h1 align="center"><img width=25px src="https://community.chocolatey.org/content/packageimages/microsoft-windows-terminal.0.2.1831.001.png"> PowerShell Tweaks (Scripts)</h1>

<h3 align="center"><img width=20px src="https://cdn-icons-png.flaticon.com/128/7425/7425907.png"> Personalization</h3>


<details><summary><b><img width=20px src="https://raw.githubusercontent.com/awesome-windows11/site/main/icon/moon.png"> Set Dark Theme</b></summary>
  
  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize" /v AppsUseLightTheme /t REG_DWORD /d 0 /f
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize" /v SystemUsesLightTheme /t REG_DWORD /d 0 /f
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize" /v EnableTransparency /t REG_DWORD /d 1 /f
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://steamuserimages-a.akamaihd.net/ugc/1809887800478745061/3ECDD5E87CF66532103B2A6991728155ACFEF2F8/?imw=512&amp;imh=367&amp;ima=fit&amp;impolicy=Letterbox&amp;imcolor=%23000000&amp;letterbox=true"> Disable Change Wallpaper</b></summary>
  
  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\ActiveDesktop" /v NoChangingWallPaper /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\ActiveDesktop" /v NoChangingWallPaper /t REG_DWORD /d 1 /f
  pause
  ```
  
  [Windows 11 обои скачать](https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/wallpaper/)

  Стандартно обои хранятся по пути:
	
  ```
  C:\Windows\Web
  ```
	
  ![image](https://user-images.githubusercontent.com/86190960/122684534-8785cc80-d20e-11eb-850b-84054ad55fd3.png)


</details>

<details><summary><b><img width=20px src="https://www.xda-developers.com/files/2021/06/Windows-11_Wallpaper_img100-1024x576.jpg"> Disable LockScreen Spotlight</b></summary>
  
  ```powershell
  reg add "HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v DisableWindowsSpotlightWindowsWelcomeExperience /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Personalization" /v NoChangingLockScreen /t REG_DWORD /d 0 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v DisableWindowsSpotlightFeatures /t REG_DWORD /d 1 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v DisableWindowsSpotlightOnActionCenter /t REG_DWORD /d 1 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v DisableWindowsSpotlightOnSettings /t REG_DWORD /d 1 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v DisableThirdPartySuggestions /t REG_DWORD /d 1 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v ConfigureWindowsSpotlight /t REG_DWORD /d 2 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v IncludeEnterpriseSpotlight /t REG_DWORD /d 0 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager" /v "RotatingLockScreenEnabled" /t REG_DWORD /d 0 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager" /v "LRotatingLockScreenEnabled" /t REG_DWORD /d 0 /f
  reg add "HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager" /v "RotatingLockScreenOverlayEnabled" /t REG_DWORD /d 0 /f
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/explorer.png"> Clean Explorer</b></summary>
  
  Force File Explorer to open to This PC instead of Quick Access

  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced" /v LaunchTo /t REG_DWORD /d 1 /f
  ```

  ```powershell
  echo 3D Objects
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{31C0DD25-9439-4F12-BF41-7FF4EDA38722}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{31C0DD25-9439-4F12-BF41-7FF4EDA38722}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  echo Videos
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{35286a68-3c57-41a1-bbb1-0eae73d76c95}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{35286a68-3c57-41a1-bbb1-0eae73d76c95}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  echo Documents
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{f42ee2d3-909f-4907-8871-4c22fc0bf756}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{f42ee2d3-909f-4907-8871-4c22fc0bf756}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  echo Downloads
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{7d83ee9b-2244-4e70-b1f5-5393042af1e4}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{7d83ee9b-2244-4e70-b1f5-5393042af1e4}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  echo Images
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{0ddd015d-b06c-45d5-8c4c-f59713854639}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{0ddd015d-b06c-45d5-8c4c-f59713854639}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  echo Music
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{a0c69a99-21c8-4671-8703-7934162fcf1d}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{a0c69a99-21c8-4671-8703-7934162fcf1d}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  echo Desktop
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{B4BFCC3A-DB2C-424C-B029-7FE99A87C641}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Explorer\FolderDescriptions\{B4BFCC3A-DB2C-424C-B029-7FE99A87C641}\PropertyBag" /v ThisPCPolicy /t REG_SZ /d Hide /f
  taskkill /F /IM explorer.exe
  start explorer.exe
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://raw.githubusercontent.com/awesome-windows11/site/main/clean.png"> Clean Taskbar</b></summary>
  
  Edit Taskbar:
  ```cmd
  %UserProfile%\AppData\Roaming\Microsoft\Internet Explorer\Quick Launch\User Pinned\TaskBar
  ```
  
  ```powershell
  echo "Disable Meet Now"
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer" /v HideSCAMeetNow /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer" /v HideSCAMeetNow /t REG_DWORD /d 1 /f
  echo "Disable People"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Explorer" /v HidePeopleBar /t REG_DWORD /d 1 /f
  reg add "HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer" /v HidePeopleBar /t REG_DWORD /d 1 /f
  echo "Hide People"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced\People" /v PeopleBand /t REG_DWORD /d 0 /f
  echo "Disable Weather, News and Interests on taskbar"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v EnableFeeds /t REG_DWORD /d 0 /f
  echo "Hide Weather, News and Interests on taskbar"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Feeds" /v ShellFeedsTaskbarViewMode /t REG_DWORD /d 2 /f
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_16826.ico"> Clean Settings</b></summary>
  
  ```powershell
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer" /v AllowOnlineTips /t REG_DWORD /d 0 /f
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/start.png"></img> Edit StartMenu</b></summary>

StartMenu Global:
  ```cmd
  C:\ProgramData\Microsoft\Windows\Start Menu\Programs
  ```

StartMenu Local:
  ```cmd
  %UserProfile%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs
  ```

</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/start.png"></img> Fix StartMenu (Does not open?)</b></summary>

  ```cmd
  Get-AppxPackage Microsoft.Windows.ShellExperienceHost | foreach {Add-AppxPackage -register "$($_. InstallLocation)\appxmanifest.xml" -DisableDevelopmentMode}

  ```

</details>

<details><summary><b><img width=20px src="https://cdn-icons-png.flaticon.com/512/1545/1545241.png"> Adding App to the Context Menu</b></summary>
  
  ```powershell
  reg add "HKEY_CLASSES_ROOT\Directory\Background\shell\VScode" /ve /d "&VScode" /f
  reg add "HKEY_CLASSES_ROOT\Directory\Background\shell\VScode\command" /ve /d "D:\Apps\VSCode\code.exe" /f
  pause
  ```
</details>

<details><summary><b>🎨 Icons</b></summary>

  [Пак всех иконок из Windows 11](https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/)
  <br>
  [shell32.dll](https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32.dll) - оригинальный файл из папки System32 в Windows 11

  <a href="https://ibb.co/48GyYLn"><img src="https://i.ibb.co/48GyYLn/122690033-9d57b980-d22f-11eb-951b-887765151e81.png" alt="122690033-9d57b980-d22f-11eb-951b-887765151e81"></a>

</details>

<h3 align="center">🛠 Apps</h3>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/check.png"></img> Remove and Disable Windows PC Health Check</b></summary>
  
  
  ```powershell
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PCHC" /v PreviousUninstall /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PCHealthCheck" /v installed /t REG_DWORD /d 1 /f
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/store.png"></img> Restore Microsoft Store Apps</b></summary>
  
  **WindowsStore**
  ```powershell
  Get-AppXPackage *WindowsStore* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}
  ```
  OR
  ```powershell
  wsreset.exe -i
  ```

  **AppInstaller (winget)**
  ```powershell
  Get-AppXPackage *AppInstaller* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}
  ```

  **WindowsTerminal**
  ```powershell
  Get-AppXPackage *WindowsTerminal* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}
  ```

  **Notepad**
  ```powershell
  Get-AppXPackage *Notepad* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}
  ```

  **Gadgets**
  ```powershell
  Get-AppXPackage *Windows.Client.WebExperience* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/store.png"></img> Remove Microsoft Store Apps</b></summary>
  
  **WindowsPhone**
  ```powershell
  Get-AppxPackage *YourPhone* | Remove-AppxPackage
  Get-AppxPackage -allusers *YourPhone* | Remove-AppxPackage
  Get-AppxProvisionedPackage –online | where-object {$_.packagename –like "*YourPhone*"} | Remove-AppxProvisionedPackage –online
  ```

  **AppInstaller (winget)**
  ```powershell
  Get-AppxPackage *AppInstaller* | Remove-AppxPackage
  Get-AppxPackage -allusers *AppInstaller* | Remove-AppxPackage
  Get-AppxProvisionedPackage –online | where-object {$_.packagename –like "*AppInstaller*"} | Remove-AppxProvisionedPackage –online
  ```

  **WindowsTerminal**
  ```powershell
  Get-AppxPackage *WindowsTerminal* | Remove-AppxPackage
  Get-AppxPackage -allusers *WindowsTerminal* | Remove-AppxPackage
  Get-AppxProvisionedPackage –online | where-object {$_.packagename –like "*WindowsTerminal*"} | Remove-AppxProvisionedPackage –online
  ```

  **Notepad**
  ```powershell
  Get-AppxPackage *Notepad* | Remove-AppxPackage
  Get-AppxPackage -allusers *Notepad* | Remove-AppxPackage
  Get-AppxProvisionedPackage –online | where-object {$_.packagename –like "*Notepad*"} | Remove-AppxProvisionedPackage –online
  ```

  **Gadgets**
  ```powershell
  Get-AppxPackage *Windows.Client.WebExperience* | Remove-AppxPackage
  Get-AppxPackage -allusers *Windows.Client.WebExperience* | Remove-AppxPackage
  Get-AppxProvisionedPackage –online | where-object {$_.packagename –like "*Windows.Client.WebExperience*"} | Remove-AppxProvisionedPackage –online
  ```
</details>


<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/store.png"></img> Remove ALL Microsoft Store Apps (NOT Microsoft Store)</b></summary>
  
  ```powershell
  Get-AppxPackage -AllUsers | where-object {$_.name –notlike "*store*"} | Remove-AppxPackage
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/store.png"></img> Remove ALL Microsoft Store Apps</b></summary>
  
  ```powershell
  Get-AppxPackage | Remove-AppxPackage
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/edge.png"></img> Remove Microsoft Edge</a></b></summary>

  > **Warning**
  > <br>
  > **This tweak is the most secure and does not break updates**

  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer\DisallowRun" /v "1" /d "msedge.exe" /f
  ```
  > **Warning**
  > <br>
  > **DANGEROUS: THE TWEAK WILL BREAK NEW UPDATES AND FEATURE INSTALLATIONS!**

  https://github.com/awesome-windows11/windows11/blob/main/remove_edge.bat

  ![image](https://user-images.githubusercontent.com/86190960/149354515-9eda8fc4-9b4e-4d3c-ba5f-5e42e62ef562.png)
  ![image](https://user-images.githubusercontent.com/86190960/149354515-9eda8fc4-9b4e-4d3c-ba5f-5e42e62ef562.png)
  ![image](https://user-images.githubusercontent.com/86190960/149354585-d467a0fe-60db-4a9b-82a6-20ea0f40934e.png)
</details>

<details><summary><b><img width=20px src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png"></img> VsCode Default Editor</a></b></summary>
  
  Сделать VScode Portable редактором по умолчанию
  <br>
  > **Warning**
  > <br>
  > **Смените путь к редактору на свой!** (по умолчанию `E:\VScode`)
  
  ![image](https://user-images.githubusercontent.com/87380272/183214790-4ed90003-a692-438f-b152-210a45fa2bd6.png)
  
  ```powershell
  # "Default Path: E:\VSCode"
  # "https://medium.com/@fawwazyusran/create-a-portable-ide-with-visual-studio-code-fb0c6bc198ef"
  
  reg add "HKEY_CLASSES_ROOT\*\shell\Custom\shell\VsCode" /ve /d "Edit with VSCode" /f
  reg add "HKEY_CLASSES_ROOT\*\shell\Custom\shell\VsCode" /v Icon /d "E:\VSCode\Code.exe,0" /f
  reg add "HKEY_CLASSES_ROOT\*\shell\Custom\shell\VsCode\command" /ve /d "\"E:\VSCode\Code.exe\" "\"%1\" /f
  
  # "This will make it appear when you right click ON a folder"
  # "The "Icon" line can be removed if you don't want the icon to appear"
  
  reg add "HKEY_CLASSES_ROOT\Directory\shell\vscode" /ve /d "Open Folder as VS Code Project" /f
  reg add "HKEY_CLASSES_ROOT\Directory\shell\vscode" /v Icon /d "E:\VSCode\Code.exe,0" /f
  reg add "HKEY_CLASSES_ROOT\Directory\shell\vscode\command" /ve /d "\"E:\VSCode\Code.exe\" "\"%1\" /f
  
  # "This will make it appear when you right click INSIDE a folder"
  # "The Icon line can be removed if you don't want the icon to appear"
  
  reg add "HKEY_CLASSES_ROOT\Directory\Background\shell\vscode" /ve /d "Open Folder in VS Code Project" /f
  reg add "HKEY_CLASSES_ROOT\Directory\shell\vscode" /v Icon /d "E:\VSCode\Code.exe,0" /f
  reg add "HKEY_CLASSES_ROOT\Directory\Background\shell\vscode\command" /ve /d "\"E:\VSCode\Code.exe\" "\"%V\" /f
  ```
  
</details>


<h3 align="center">📜 Policies</h3>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/defender.png"> Disable Windows Defender</b></summary>

  Source: https://admx.help/HKLM/Software/Policies
  
  > **Warning**
  > <br>
  > **Установите перед использованием [gsudo](https://github.com/gerardog/gsudo/releases/download/v1.3.0/gsudoSetup.msi)!**
  
  ```powershell
  gsudo -s powershell.exe
  ```

  ```powershell
  # "Disable Windows Defender"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableRealtimeMonitoring /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiVirus /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableSpecialRunningModes /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableRoutinelyTakingAction /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v ServiceKeepAlive /t REG_DWORD /d 0 /f
  # "Disable RealTimeProtection"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableBehaviorMonitoring /t REG_DWORD /d 1 /f
  # "Disable AccessProtection"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableOnAccessProtection /t REG_DWORD /d 1 /f
  # "Disable ScanProcess"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableScanOnRealtimeEnable /t REG_DWORD /d 1 /f
  # "Disable ScanDownloadFiles"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableIOAVProtection /t REG_DWORD /d 1 /f
  # "Disable VirusNotification"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableRealtimeMonitoring /t REG_DWORD /d 1 /f
  # "Disable AppControl (Windows Store)"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\SmartScreen" /v ConfigureAppInstallControlEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Signature Updates" /v ForceUpdateFromMU /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Spynet" /v DisableBlockAtFirstSeen /t REG_DWORD /d 1 /f
  # "Disable automatic sample submission and Spynet community membership"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Spynet" /v SubmitSamplesConsent /t REG_DWORD /d 2 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Spynet" /v SpynetReporting /t REG_DWORD /d 0 /f
  # "Disable TamperProtection"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender\Features" /v TamperProtection /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender" /v ServiceStartStates /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender" /v DisableAntiVirus /t REG_DWORD /d 1 /f
  pause
  ```
  Optional settings:
  ```powershell
  # Windows Defender Advanced Threat Protection
  sc config WinDefend start=disabled >nul && net stop WinDefend >nul
  sc config SecurityHealthService start=disabled >nul
  sc config Sense start=disabled >nul
  sc config WdNisDrv start=disabled >nul
  sc config WdNisSvc start=disabled >nul
  reg delete "HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Run" /v "SecurityHealth" /f

  # Служба которая висит в трее панели задач (значок защитника), отключение убивает UI защитника
  reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\SecurityHealthService" /v Start /t REG_DWORD /d 4 /f
  # Служба которая сканирует файлы и убивает HDD, само тело службы защитника
  reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\WinDefend" /v Start /t REG_DWORD /d 4 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender\Real-Time Protection" /v DisableRealtimeMonitoring /t REG_DWORD /d 1 /f
  
  reg add "HKLM\SOFTWARE\Policies\Microsoft\MRT" /v DontOfferThroughWUA /t REG_DWORD /d 1 /f 
  reg add "HKLM\SOFTWARE\Policies\Microsoft\MRT" /v DontReportInfectionInformation /t REG_DWORD /d 1 /f
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/update.png"></img> Disable Windows Update</b></summary>
  
  > **Warning**
  > <br>
  > **Установите перед использованием [gsudo](https://github.com/gerardog/gsudo/releases/download/v1.3.0/gsudoSetup.msi)!**
  
  ```powershell
  # "Disable OS Upgrade"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate" /v DisableOSUpgrade /t REG_DWORD /d 1 /f
  # "Disable Scanning, Downloading and Installing Updates"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate" /v SetDisableUXWUAccess /t REG_DWORD /d 1 /f
  # "Disable AutoUpdate"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU" /v NoAutoUpdate /t REG_DWORD /d 1 /f
  # "Enable NotificationUpdate"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU" /v AUOptions /t REG_DWORD /d 2 /f
  # "Scheduled Every Day (AUOptions = 4!)"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU" /v ScheduledInstallDay /t REG_DWORD /d 0 /f
  # "Scheduled Time Hour (0 -> 23)"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU" /v ScheduledInstallTime /t REG_DWORD /d 3 /f
  # "Disable AutoInstall Drivers"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DriverSearching" /v SearchOrderConfig /t REG_DWORD /d 0 /f
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/store.png"></img> Disable Apps Microsoft Store AutoUpdate and Force Install</b></summary>

  ```powershell
  # "Disable AutoUpdate Apps Microsoft Store"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent" /v DisableWindowsConsumerFeatures /t REG_DWORD /d 1 /f
  # "Block the automatic installation of suggested Windows 10 apps"
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\ContentDeliveryManager" /v SilentInstalledAppsEnabled /t REG_DWORD /d 0 /f
  # "Disable Showing App Suggestions in Start in Windows 10 (settings app)"
  reg add "HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager" /v SubscribedContent-338388Enabled /t REG_DWORD /d 0 /f
  # "Disable OEM Apps"
  reg add "HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager" /v OemPreInstalledAppsEnabled /t REG_DWORD /d 0 /f
  # "Disable Promotional Apps"
  reg add "HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager" /v PreInstalledAppsEnabled /t REG_DWORD /d 0 /f
  pause
  ```
</details>


<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/cortana.png"></img> Disable Cortana</b></summary>

  ```powershell
  # "Disable Cloud Search"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Search" /v AllowCloudSearch /t REG_DWORD /d 0 /f
  # "Disable Cortana"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Search" /v AllowCortana /t REG_DWORD /d 0 /f
  # "Disable Cortana LockScreen"
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Search" /v AllowCortanaAboveLock /t REG_DWORD /d 0 /f
  # "Disable Cortana"
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search" /v CortanaEnabled /t REG_DWORD /d 0 /f
  # "Disable Cortana"
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search" /v CortanaConsent /t REG_DWORD /d 0 /f
  pause
  ```
</details>


<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/edge.png"></img> Microsoft Edge Lite (NOT Sync Microsoft Account)</b></summary>
  
  ```powershell
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v SyncDisabled /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v BrowserSignin /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v NewSmartScreenLibraryEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v SmartScreenEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v SmartScreenPuaEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v StartupBoostEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v BingAdsSuppression /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v BackgroundModeEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v ComponentUpdatesEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v EdgeShoppingAssistantEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v ForceGoogleSafeSearch /t REG_DWORD /d 1 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Edge" /v MAUEnabled /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\EdgeUpdate" /v AutoUpdateCheckPeriodMinutes /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\EdgeUpdate" /v UpdateDefault /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\EdgeUpdate" /v UpdatePolicy /t REG_DWORD /d 0 /f
  reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft" /v DoNotUpdateToEdgeWithChromium /t REG_DWORD /d 1 /f
  pause
  ```
</details>

<details><summary><b><img width=20px src="https://icons.iconarchive.com/icons/dtafalonso/android-lollipop/512/Chrome-icon.png"> Chrome Lite (NOT Security, etc.)</b></summary>
  
  https://github.com/awesome-windows11/chrome
</details>

<details><summary><b><img width=20px src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/Firefox_logo%2C_2019.svg/1200px-Firefox_logo%2C_2019.svg.png"> Firefox Lite (NOT Sync Account, Pocket, etc.)</b></summary>
  
  https://github.com/awesome-windows11/firefox#-policiesjson
</details>

<h3 align="center"> <img width=25px src="https://i.ibb.co/5KpSCNv/win11.png"> Win11</h3>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/explorer.png"> Switch Explorer (Restore The Ribbon)</b></summary>
  
  ![image](https://user-images.githubusercontent.com/87380272/184669919-f84bccc8-aa31-4f3a-8bed-98230aa8fef0.png)

  **New Explorer (Win11)**
  ```powershell
  reg delete "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}" /f
  taskkill /F /IM explorer.exe
  start explorer.exe
  ```

  **Old Explorer (Win10)**
  ```powershell
  reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve
  taskkill /F /IM explorer.exe
  start explorer.exe
  ```

</details>

<details><summary><b><img width=20px src="https://site-iota-coral.vercel.app/icon/context.png"> Switch Context Menu (New, old)</b></summary>
  
  ![image](https://user-images.githubusercontent.com/87380272/184685122-69e70453-acc8-469d-88ec-3f525e085d97.png)
  ![image](https://user-images.githubusercontent.com/86190960/124923114-d26f5480-e002-11eb-8935-ea1d777d8425.png)

  **New Menu (Win11)**
  ```powershell
  reg delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f
  taskkill /F /IM explorer.exe
  start explorer.exe
  ```

  **Old menu (Win10)**
  ```powershell
  reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
  taskkill /F /IM explorer.exe
  start explorer.exe
  ```

</details>

<details><summary><b> <img width=20px src="https://cdn-icons-png.flaticon.com/512/6585/6585361.png"> TaskBar Size (Small, medium, big)</b></summary>

  ![image](https://user-images.githubusercontent.com/86190960/122673593-bfbee800-d1d9-11eb-8af7-aece6bea23d7.png)![image](https://user-images.githubusercontent.com/87380272/184697771-360498b3-207d-4873-a91e-139d5928da91.png)
  
  **Small TaskBar**

  ```powershell
  reg add "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced" /v TaskbarSi /t REG_DWORD /d 0 /f
  taskkill /F /IM explorer.exe
  start explorer.exe  
  ```

  **Medium TaskBar**

  ```powershell
  reg add "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced" /v TaskbarSi /t REG_DWORD /d 1 /f
  taskkill /F /IM explorer.exe
  start explorer.exe  
  ```

  ### Big TaskBar

  ```powershell
  reg add "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced" /v TaskbarSi /t REG_DWORD /d 2 /f
  taskkill /F /IM explorer.exe
  start explorer.exe  
  ```
</details>

<details><summary><b> <img width=20px src="https://cdn-icons-png.flaticon.com/512/6585/6585361.png"> TaskBar Layout (Top, bottom)</b></summary>

  ![image](https://user-images.githubusercontent.com/86190960/149355038-60bd0c3e-cec0-4ca7-bab3-16bccfa4d597.png)

  Change the location of the taskbar

  **Up TaskBar ⬆**

  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3" /v Settings /t REG_BINARY /d 30000000feffffff0200000001000000300000002000000000000000c203000080070000e20300006000000001000000 /f
  ```

  **Down TaskBar ⬇**

  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3" /v Settings /t REG_BINARY /d 30000000feffffff0200000003000000300000002000000000000000c203000080070000e20300006000000001000000 /f
  ```

  **Left TaskBar ⬅**

  > **Warning**
  > <br>
  > Causes bugs, do not use!

  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3" /v Settings /t REG_BINARY /d 30000000feffffff0200000000000000300000002000000000000000c203000080070000e20300006000000001000000 /f
  ```

  **Right TaskBar ➡**

  > **Warning**
  > <br>
  > Causes bugs, do not use!

  ```powershell
  reg add "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3" /v Settings /t REG_BINARY /d 30000000feffffff0200000002000000300000002000000000000000c203000080070000e20300006000000001000000 /f
  ```
</details>

<h1 align="center"><img width=25px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_302.ico"> ISO Windows</h1>

<h3 align="center">Download ISO</h3>

  https://uupdump.net
  <br>
  https://tb.rg-adguard.net/public.php
  <br>
  https://uup.rg-adguard.net
  <br>
  [Windows ISO Downloader](https://www.heidoc.net/joomla/technology-science/microsoft/67-microsoft-windows-and-office-iso-download-tool)
  <br>
  https://github.com/pbatard/Fido

<h3 align="center">⬇ Install ISO</h3>

  [❗ My files](https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ)
  <br>
  <img width=20px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_302.ico"> [MBR to GPT (without data loss)](http://www.it.nrru.ac.th/download/utilities/pwfree9.exe)
  <br>
  Insider without Microsoft Account: https://github.com/abbodi1406/offlineinsiderenroll
  <br>
  https://github.com/pbatard/rufus
  <br>
  https://github.com/ventoy/Ventoy
  <br>
  https://github.com/AveYo/MediaCreationTool.bat
  <br>
  Dism++: https://github.com/Chuyu-Team/Dism-Multi-language
  <br>
  WinNTSetup: http://wntsetup.ru
  <br>
  WinISO: https://rsload.net/soft/cleaner-disk/10195-winiso.html
  <br>
  [Windows Insider Build ISO](https://www.microsoft.com/en-us/software-download/windowsinsiderpreviewiso)
  <br>
  [Rectify11](https://rectify.vercel.app)
  <br>
  [BlissOS](https://blissos.org/index.html)

<h3 align="center">💽 Bypass TPM</h3>

  [TPM: About, Installer, Bypass, FAQ](https://github.com/awesome-windows11/windows11/wiki/%F0%9F%92%BD-TPM)
  <br>
  https://github.com/quickfever/Windows-11-Bypass-TPM
  <br>
  https://github.com/haithamaouati/BypassWin11
  <br>
  https://github.com/shirooo39/Windows-11-Bypass
  <br>
  https://github.com/rushiranpise/win11devbypass
  <br>
  https://github.com/FrancescoDiSalesGithub/TPM-windows11-hack

<h3 align="center">Boot, VHD (Virtual Disks)</h3>

  https://rsload.net/soft/11768-easybcd.html
  <br>
  https://www.sordum.org/8705/simple-vhd-manager-v1-4

<h3 align="center">Hash ISO</h3>

  [💿 Known ISO file hashes (check for originality)](https://github.com/awesome-windows11/windows11/wiki/%F0%9F%92%BF-ISO)
  <br>
  https://msdn.rg-adguard.net
  <br>
  https://sha1.rg-adguard.net
  <br>
  https://www.heidoc.net/php/myvsdump_directory.php?letter=W
  <br>
  https://files.rg-adguard.net/version/f0bd8307-d897-ef77-dbd6-216fefbe94c5
  <br>
  https://github.com/AndrewRathbun/VanillaWindowsReference

<h3 align="center">Versions Windows</h3>

  https://github.com/awesome-windows11/windows11/tree/main/version
  <br>
  https://changewindows.org/timeline/pc

<h1 align="center">Apps</h1>

<h2 align="center"><img width=25px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_16.ico"> System Tools</h1>

<details><summary><b><img width=20px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_25.ico"> AutoRun</b></summary>

  Hidden Apps AutoRun: https://www.nirsoft.net/utils/what_run_in_startup.html
  <br>
  AutoRuns: https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns

</details>

<details><summary> <b><img width=20px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_302.ico"> Disk</b></summary>

  <h3 align="center">Manager Partition</h3>

  MiniTool Partition Wizard Free: https://www.partitionwizard.com/free-partition-manager.html
  <br>
  AOMEI Partition Assistant: https://www.diskpart.com/free-partition-manager.html

  <h3 align="center">SSD Info</h3>

  CrystalDiskInfo: https://crystalmark.info/en/download/#CrystalDiskInfo
  <br>
  CrystalDiskMark: https://crystalmark.info/en/download/#CrystalDiskMark
  <br>
  IsMyHdOK: https://www.softwareok.com/?Download=IsMyHdOK
  <br>
  Hard Disk Sentinel: https://www.hdsentinel.com/download.php
  <br>
  Victoria: https://hdd.by/victoria
  <br>
  ClearDiskInfo: https://www.carifred.com/cleardiskinfo
</details>

<details><summary><b><img width=20px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_32.ico"> Uninstaller</b></summary>

  BCUninstaller: https://github.com/Klocman/Bulk-Crap-Uninstaller
  <br>
  UninstallTool: https://crystalidea.com/ru/uninstall-tool
  <br>
  https://lockhunter.com
</details>

<details><summary><b><img width=20px src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Shield/3D/shield_3d.png"> Management (Security)</b></summary>

  https://defaultprogramseditor.com
  <br>
  <img width=20px src="https://raw.githubusercontent.com/SiL3NC3/PortableRegistrator/master/Resources/Wallpaperfx-3d-Bluefx-Desktop-Usb.png"> https://github.com/SiL3NC3/PortableRegistrator
  <br>
  SafeMode Launcher: https://www.sordum.org/12964/safe-mode-launcher-v1-1
  <br>
  Compressor CompactOS: https://github.com/IridiumIO/CompactGUI
</details>


<details><summary><b><img width=20px src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Globe%20showing%20americas/3D/globe_showing_americas_3d.png"> Internet</b></summary>

  qBittorrent: https://portableapps.com/apps/internet/qbittorrent_portable
  <br>
  URL Disabler: https://www.sordum.org/13075/url-disabler-v1-1

</details>


<details><summary><b> <img width=20px src="https://cdn-icons.flaticon.com/png/512/3672/premium/3672629.png?token=exp=1659819914~hmac=3e43fd18dcd3033d8553dfd15a0a37c4"> Virtual</b></summary>

  <img width=20px src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Virtualbox_logo.png"> https://www.virtualbox.org/wiki/Downloads
  <br>
  <img width=20px src="https://cdni.comss.net/logo/sandboxie_icon.png"></img> https://github.com/sandboxie-plus/Sandboxie

</details>

<details><summary><b> <img width=20px src="https://cdn-icons-png.flaticon.com/512/1400/1400975.png"> Driver</b></summary>

  Snappy Driver Installer: https://sdi-tool.org/download
  <br>
  G-Hub: https://www.logitechg.com/ru-ru/innovation/g-hub.html

</details>


<details><summary><b>Activators</b></summary>

  ### <a target="_blank" href="https://github.com/awesome-windows11/windows11/releases/tag/99">🔓 Activator by Ratiborus</a>

  https://github.com/massgravel/Microsoft-Activation-Scripts
	
  https://github.com/newmen93/W10-Digital-License-Activation-Script-4

  В AAct все операции с активацией, с лицензиями, выполняются с помощью стандартных скриптов slmgr.vbs и ospp.vbs, уж их то даже самый ненормальный антивирусник не заподозрит в "троянстве".

  http://forum.ru-board.com/topic.cgi?forum=2&topic=5559

  <details>
    <summary> В чём отличие KMSAuto Net 2016 1.5.0 и Portable AAct?</summary>
    Принципиальное отличие этих двух программ в том, что у первой для работы программы требуется .NET Framework 4.5 , а вот для второй НЕ требуется .NET Framework, работает на Windows XP - 10.
    <br><br>
    С другой стороны KMSAuto Net имеет намного больше возможностей по настройке процесса активации, чем AAct и иногда позволяет решить проблемы с KMS-активацией там, где AAct не справляется. Или, если использовать автомобильную терминологию, первая программа является высокоэффективной ручной коробкой передач, позволяющей опытному водителю использовать ее возможности по максимуму, в то время как вторая программа является "автоматом", более подходящим для новичков и домохозяек.
  </details>
</details>



<h2 align="center">User Tools</h1>

<details><summary><b><img width=20px src="https://filedn.eu/lFS6h5cBEsru02lgr5VwkTJ/Windows%2011%20Files/icons/shell32_236.ico"> Media (Photo, Video, Audio)</b></summary>

  PaintNet: https://www.dotpdn.com/downloads/pdn.html
  <br>
  Open `.ogg` file: https://apps.microsoft.com/store/detail/web-media-extensions/9N5TDP8VCMHS
  <br>
  Windows Media Player: https://apps.microsoft.com/store/detail/windows-media-player/9WZDNCRFJ3PT
</details>

<details><summary><b> <img width=20px src="https://cdn-icons-png.flaticon.com/512/7754/7754226.png"> Hash</b></summary>

  https://github.com/gurnec/HashCheck
  <br>
  https://hashtab.ru
  <br>
  https://github.com/tristanheaven/gtkhash
  <br>
  [HashMyFiles](https://www.nirsoft.net/utils/hash_my_files.html)
  <br>
  http://getmd5checker.com
</details>

<details><summary><b> <img width=20px src="https://cdn-icons.flaticon.com/png/512/4906/premium/4906326.png?token=exp=1659819721~hmac=793c3499d47b6e2495e248b010477f07"> Double-click mouse fix</b></summary>

  ### Проверка
  https://alexbruni.ru/checkmouse
  <br>
  https://codepen.io/blink172/pen/vERyxK
  <br>
  ### Исправить
  https://www.clickfix.cf

  https://www.softpedia.com/get/System/System-Miscellaneous/Left-Mouse-Button-Fix.shtml
</details>




<details><summary><b><img width=20px src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Mobile%20phone/3D/mobile_phone_3d.png"> Win11 APK</b></summary>

  APK Installer 1: [An APK File Installer for WSA](https://apps.microsoft.com/store/detail/apk-file-installer/9MVVJLDMWPSG)
  <br>
  APK Installer 2: [WSATools](https://apps.microsoft.com/store/detail/9N4P75DXL6FG)
  <br>
  APK Installer 3: https://github.com/voletro/wsa-toolbox
  <br>
  Google Play Installer: https://github.com/ADeltaX/WSAGAScript
</details>



<details><summary><b>🔔 Compatibility check (Win11)</b></summary>

  https://github.com/rcmaehl/WhyNotWin11
  <br>
  https://github.com/mq1n/Win11SysCheck
</details>



<h1 align="center">Tweaks</h1>

| Скачать | Описание |
| -------- | --------- |
| [InputSwitch.zip](https://github.com/awesome-windows11/windows11/blob/main/archive/InputSwitch.zip?raw=true) <br> ![image](https://user-images.githubusercontent.com/86190960/149355219-377f3d65-d638-4937-bfa7-69e24332eab3.png) | Отключить / включить всплывающую панель

<h1 align="center">❓ FAQ</h1>

```powershell
# Как закрепить UWP на рабочий стол?
shell:AppsFolder
```
```powershell
# Посмотреть все приложения UWP
Get-AppxPackage –AllUsers | Select Name, PackageFullName
```
```powershell
# Полная команда, для подробного анализа
Get-AppxPackage –AllUsers
```
<img width="40%" src="https://user-images.githubusercontent.com/86190960/125692295-e047e2fd-1fc8-414f-860c-4e12deec2bc3.png"></img><img width="40%" src="https://user-images.githubusercontent.com/86190960/125692307-e8b3f2d6-55c7-48c5-bb2e-c642afeb20bb.png"></img>

## Как исправить кракозябры?
<a href="https://user-images.githubusercontent.com/86190960/122917450-b57e2480-d366-11eb-9e2b-96925e556b59.png"><img src="https://i.ibb.co/DWHgjcw/image.png" alt="image" border="0"></a>

Включите русский язык по умолчанию в Параметры -> "Time&Language" -> "Language" -> "Administrative language settings" -> "Язык программ, не поддерживающих Юникод" -> "Изменить язык системы..." -> "Russia"

<a href="https://user-images.githubusercontent.com/86190960/122917560-d5ade380-d366-11eb-80fd-be4a6f7c57f3.png"><img src="https://i.ibb.co/NC6vGdt/image.png" alt="image" border="0"></a> 
<a href="https://user-images.githubusercontent.com/86190960/122917570-d8103d80-d366-11eb-9164-a6fbbf415a90.png"><img src="https://i.ibb.co/5knF8qh/image.png" alt="image" border="0"></a>
<a href="https://user-images.githubusercontent.com/86190960/122917584-db0b2e00-d366-11eb-8793-96259bac5965.png"><img src="https://i.ibb.co/mbY4RHH/image.png" alt="image" border="0"></a>

## Как посмотреть последние файлы открытые на ПК?
```
%UserProfile%\AppData\Roaming\Microsoft\Windows\Recent
```
## Как включить режим бога панель управления (GodMode?)
Создайте папку с именем:
```
Settings.{ED7BA470-8E54-465E-825C-99712043E01C}
```

<h1 align="center">🔗 Links</h1>

Реестр проводника:
- http://www.rusdoc.ru/material/os/win/reestr.shtml
- https://ss64.com/nt/syntax-reghacks.html
- http://centaz.narod.ru/winwork2.html

Памятка по командной строке (cmd.exe):
- https://ab57.ru/cmdlist.html
- https://renenyffenegger.ch/notes/Windows
- https://admx.help


<h1 align="center">Stats</h1>

[![Stargazers over time](https://starchart.cc/awesome-windows11/windows11.svg)](https://starchart.cc/awesome-windows11/windows11)
