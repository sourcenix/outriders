# outriders
**Requires Windows Defender**
<br/>
In order to fix stuttering issues with Outriders I had to exclude the games executables from Windows Defender. The exclusions can be added with powershell.

Run the following PowerShell commands as administrator (right click PowerShell, "Run as Administrator") to add the required Windows Defender Exceptions for Outriders. Remember to update the path if you have installed to a different location.

```
Add-MpPreference -ExclusionProcess "C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\OUTRIDERS-Win64-Shipping.exe"
Add-MpPreference -ExclusionProcess "C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\EAC_OUTRIDERS.exe"
Add-MpPreference -ExclusionProcess "C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\Madness\Binaries\Win64\OUTRIDERS-Win64-Shipping.exe"
```
<br/>
Alternatively, if you have another Antivirus solution you can exclude the following executables while following you products documentation:<br/>
* C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\OUTRIDERS-Win64-Shipping.exe
* C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\EAC_OUTRIDERS.exe
* C:\Program Files (x86)\Steam\steamapps\common\OUTRIDERS\Madness\Binaries\Win64\OUTRIDERS-Win64-Shipping.exe

