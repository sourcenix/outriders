# outriders

Run the following PowerShell commands to add the required Windows Defender Exceptions for Outriders. Remember to update the path if you have installed to a different location.

```
Add-MpPreference -ExclusionProcess "C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\OUTRIDERS-Win64-Shipping.exe"
Add-MpPreference -ExclusionProcess "C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\EAC_OUTRIDERS.exe"
Add-MpPreference -ExclusionProcess "C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\Madness\Binaries\Win64\OUTRIDERS-Win64-Shipping.exe"
```
