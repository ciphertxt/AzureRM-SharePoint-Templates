AzureRM-SharePoint-Templates
============================
Azure Resource Templates from the currrent public gallery for SharePoint.

All output from:

```powershell
Get-AzureResourceGroupGalleryTemplate | ? { $_.Identity -like "Microsoft.SharePoint*" -and $_.Publisher -eq "Microsoft" } | Save-AzureResourceGroupGalleryTemplate -Path $pwd
```
