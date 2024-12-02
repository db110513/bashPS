# Power Shell

#### kill process:
```
Get-NetTCPConnection -LocalPort NUMERO_PORT | Select-Object -ExpandProperty OwningProcess
Stop-Process -Id NUMERO_PORT -Force
```

#### canvi nom:
```
Rename-Item -Path "C:\Users\Daniel\Desktop\antic.txt" -NewName "nou.txt"
```

#### esborra dir
```
Remove-Item -Path "C:\Users\Daniel\Desktop\Directori" -Recurse
```
