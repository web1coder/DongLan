# bisligcity
system objects solutions
Donglan Advice about Visual Basic Loading Problem (09-13-2018)

Problem when loading vb6..
“User-defined type not defined” error in VB 6 under Windows 7
If your visual basic project (ver.6.0) still have a problem using Windows 7 OS and above. You can fix it by:

1. Click Start Menu and search cmd 
2. Right click cmd and select run as administrator
3. At the command prompt type cd c:\Windows\Microsoft.NET\Framework\v4.0.30319>
4. type a dos command c:\Windows\Microsoft.NET\Framework\v4.0.30319>regsvr32 MSCOMCTL.ocx
5. type a dos command c:\Windows\Microsoft.NET\Framework\v4.0.30319>regsvr32 MSCOMCT2.ocx
6. type a dos command c:\Windows\Microsoft.NET\Framework\v4.0.30319>regtlibv12 msdatsrc.tlb
6. If successful Go back to VB6 project and run it as admin. C:\Program Files (x86)\Microsoft Visual Studio\VB98 (right click vb6 application and select run as admin)
7. In your vb6 window click Project-Components. 
Click Microsoft Windows Common Controls 6.0 (SP6)
Microsoft Windows Common Controls 26.0
Click Apply and Ok. Save your project and exit.
8. Reboot your system and run your Visual Basic Project.
