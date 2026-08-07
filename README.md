# EaseX

Painel CEP para After Effects: ajuste visual de easing, influence, speed e bounce.

## Instalação rápida

Abra o PowerShell e execute:

```powershell
$u='https://github.com/brunojorri/EaseX/raw/main/EaseX-v0.1.2.zip';$z=Join-Path $env:TEMP 'EaseX.zip';$d=Join-Path $env:APPDATA 'Adobe\CEP\extensions\com.easex.panel';Invoke-WebRequest $u -OutFile $z;New-Item -ItemType Directory -Force $d|Out-Null;Expand-Archive $z -DestinationPath $d -Force;New-Item 'HKCU:\Software\Adobe\CSXS.12' -Force|Out-Null;New-ItemProperty 'HKCU:\Software\Adobe\CSXS.12' -Name PlayerDebugMode -PropertyType String -Value 1 -Force|Out-Null
```

Reinicie o After Effects e abra **Window > Extensions > EaseX**.

[Instagram profissional — @brunojorri_work](https://www.instagram.com/brunojorri_work/)
