# Microsoft LSA Proxy SSP AP
Windows LSA Authentication Package proxy example

This is simple example of Microsoft SSP/APs, SSPs providers. Hope that is help someone. If is it i've will be continue code docs and more usefull examples. Just let me know at [issue page](../../issues)  

---  

For more information please visit oficial [Microsoft white page docs](https://docs.microsoft.com/en-us/windows/win32/secauthn/ssp-aps-versus-ssps)

---
To load the SSP/AP:
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa 

There's a REG_MULTI_SZ named Authentication Packages. Add the module name, without .dll, to the next line after msv1_0
