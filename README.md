# WinDefendInjectPoC

This is the PoC for 

How to use ?

Place your desired dll to be load next to the PoC with the name "MpSvc.dll", and note that the dll must contain a service CTRL handler if you'd to keep windows defender alive, because services.exe will terminate the process if it didn't gave a responce within 30 seconds.
