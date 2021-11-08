# Install-win-11-VirtualBox

1. Download win_11.iso from microsoft. 
2. Make new Virtual box windows box, add the .iso as install disk (live cd)
3. On boot of windows 11. Press Alt + F10, Enter

```
regedit
Computer\HKEY_LOCAL_MACHINE\SYSTEM\Setup\LabConfig
BypassSecureBootCheck 1
BypassTPMCheck 1
```

4. Save
5. Continue Install. 

