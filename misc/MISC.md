## Misc

Backup Putty conf:

```
regedit /e "%userprofile%\desktop\putty.reg" HKEY_CURRENT_USER\Software\SimonTatham
```


Stop blocked port `80` on Windows:

```
%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe net stop was /y
```


Delete long path on Windows:

```
mkdir D:\empty; robocopy /MIR D:\empty D:\Some\Long\Path
```
