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

![image](https://user-images.githubusercontent.com/5285547/140798836-d8b99c80-00fc-46fe-a9d4-85d5b8c58196.png)


4. Save
5. Continue Install. 

