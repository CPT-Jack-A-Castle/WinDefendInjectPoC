# WinDefendInjectPoC

This is the PoC for https://halove23.blogspot.com/2021/08/executing-code-in-context-of-trusted.html

How to use ?

Place your desired dll to be load next to the PoC with the name "MpSvc.dll", and note that the dll must contain a service CTRL handler if you'd to keep windows defender alive, because services.exe will terminate the process if it didn't gave a responce within 30 seconds.
The PoC must be executed as "NT AUTHORITY\SYSTEM" in order to function.
