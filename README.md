# Remove apps from Windows 10 using Powershell

Start Powershell as Administrator and execute following commands:

  Removes Cortana:
- Get-AppxPackage -allusers Microsoft.549981C3F5F10 | Remove-AppxPackage

Removes other apps:
- Get-AppxPackage \*gethelp\* | Remove-AppxPackage
- Get-AppxPackage \*microsoft.people\* | Remove-AppxPackage
- Get-AppxPackage \*windowscamera\* | Remove-AppxPackage
- Get-AppxPackage \*zunemusi\c* | Remove-AppxPackage
- Get-AppxPackage \*windowsmaps\* | Remove-AppxPackage
- Get-AppxPackage \*photos\* | Remove-AppxPackage
- Get-AppxPackage \*bingweather\* | Remove-AppxPackage
- Get-AppxPackage \*getstarted\* | Remove-AppxPackage
- Get-AppxPackage \*officehub\* | Remove-AppxPackage
- Get-AppxPackage \*windowscommunicationsapps\* | Remove-AppxPackage
- Get-AppxPackage \*phone\* | Remove-AppxPackage
