# Admin-
Local $sPassword = ""   ; Place Admin Password here.
SplashTextOn(" Inc.","Running Printer IP update Please Wait.....","-1","-1","-1","-1",0,"","","")
_WriteLog("Installation Started : ")
FileInstall("C:\TS\CloudScripts\Reconfigure-Printer-V0.5.ps1","C:\ts\Reconfigure-Printer-V0.5.ps1",1)
