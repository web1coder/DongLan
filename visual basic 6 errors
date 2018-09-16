# VB6 Objects Reference
System Objects Solutions.
Visual Basic Loading Problem by DongLan (09-13-2018 Bislig City, Philippines)

Problem when loading vb6 in Windows 7 and above
1. “User-defined type not defined” error
2. "Object not registered" messages after checking controls and clicking Apply and Ok button in Project/components/controls
3. "Error accessing the system registry"  messages after checking controls and clicking Apply and Ok button in Project/components/controls

If your visual basic project (ver.6.0) still have a problem using Windows 7 OS and above. You can fix it by:

1. Click Start Menu and search cmd 
2. Right click cmd and select run as administrator
3. At the command prompt type cd c:\Windows\Microsoft.NET\Framework\v4.0.30319>
4. type a dos command c:\Windows\Microsoft.NET\Framework\v4.0.30319>regsvr32 MSCOMCTL.ocx
5. type a dos command c:\Windows\Microsoft.NET\Framework\v4.0.30319>regsvr32 MSCOMCT2.ocx
6. type a dos command c:\Windows\Microsoft.NET\Framework\v4.0.30319>regsvr32 COMCTL32.OCX
7. type a dos command c:\Windows\Microsoft.NET\Framework\v4.0.30319>regtlibv12 msdatsrc.tlb
8. If successful Go back to VB6 project and run it as admin. C:\Program Files (x86)\Microsoft Visual Studio\VB98 (right click vb6 application and select run as admin)
9. In your vb6 window click Project-Components. 
check/select Microsoft Windows Common Controls 6.0 (SP6)
check/select Microsoft Windows Common Controls 26.0
check/select Microsoft Windows Common Controls 5.0 (SP2)
Click Apply and Ok. Save your project and exit.
8. Reboot your system and run your Visual Basic Project.
