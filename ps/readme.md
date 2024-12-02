# Power Shell

#### kill process:
```
Get-NetTCPConnection -LocalPort NUMERO_PORT | Select-Object -ExpandProperty OwningProcess
Stop-Process -Id NUMERO_PORT -Force
```
