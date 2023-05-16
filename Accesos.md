# Accesos

## CMD
```
C:\Windows\system32>winrs -r:dcorp-dc cmd
Microsoft Windows [Version 10.0.20348.1249]
(c) Microsoft Corporation. All rights reserved.

C:\Users\svcadmin>
```
## Powershell
```
PS C:\Windows\system32> Enter-PSSession -ComputerName dcorp-dc
[dcorp-dc]: PS C:\Users\svcadmin\Documents>

```
## Runas
```
runas /user:user "c:\windows\system32\cmd.exe" < password.txt

```
