# w11-tutorial
Wan't to install windows 11 on unsupported hardware without usb? This will help you out!

# EN Tutorial
1. Go to ``winiso.pl`` and download Windows 11. It's quite small.
2. Navigate to your C:\ drive
3. Create folder named ``weve``
4. You are halfway done, now open Run ``CTRL+R``
5. Now input into box below <br> <img src="https://cdn.upload.systems/uploads/95qrsMQW.png">
6. Your pc will restart into advenced recovery mode.
7. Then go to Advenced options
8. And select Command Prompt
9. Now type in ``regedit``
10. Then navigate to ``HKEY_LOCAL_MACHINE -> SYSTEM -> Setup``
11. Now you will create file that will bypass TrustedMachine and SafeBoot
12. Create new key with name ``LabConfig``
13. Then create first DWORD Value that will bypass TrustedMachine 2.0:

<br>
``` 
   Registry values:

   BypassSecureBootCheck with value 1 (``Hexadecimal``)
   BypassTPMCheck with value 1 (``Hexadecimal``)
   Both are DWORD 32-Bit
```
<br>
   
14. Then you can close this regedit, BUT DON'T CLOSE CMD

15. Installation will guide you.

16. Now you are on disk step so, choose you C:\ Drive, this will give you warning but don't worry, your old files will be stored in Windows.old

17. Then the installation will begin

18. When the installation finishes your pc will reboot and you will have 2 Windows 10, select the first one. It's only name so, don't worry.

19. Now the setup will install drivers and other stuff

20. Then you will have the OOBE screen, setup your pc however you wan't

21. Then you must wait till Windows create your profile.

22. You will be greated with new windows 11 Desktop.


# Issues with screen
If your screen is weird then
<br>
  Solution 1: ``Win + L`` then login into your account  
  
  Solution 2: Restart PC
  
  Solution 3: Put your Laptop/PC in sleep mode
  
  Solution 4: Install drivers for you GPU (don't worry if there is no driver for Windows 11, drivers for Windows 10 will work too)
<br>

# Other issues
If you are having other issues then feel free to open issue and tell me what is your problem. I will try to help!

# Credits
All written by cloud3,
<br>
Last update: 9PM 01.07.2021
