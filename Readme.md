## **Update Google Chrome, Avast Secure, Chocolatey, 7zip, Hugo, GitHub CLI, Jq, Yq, Pup, XMLstarlet, Wmi Explorer, Rufus, Rainmeter and Youtube-Dl with Windows Shell**
---
##### Author: Fabrice Sanga
<br/>

The `profile.init.bat` file :
```batfile
@Echo OFF
If %~1==autorun_parent Echo Path\To\Autorun\Profile\Folder
```
<br/>

The usage :
```batfile
Update-App [CopyToDirectory]
CopyToDirectory     The directory where to backup the installer
App                 GoogleChrome, AvastSecure, Chocolatey, 7zip, Hugo, GitHubCLI,
                    Jq, Yq, Pup, XML, WmiExplorer, Rufus, Rainmeter or YoutubeDL
```