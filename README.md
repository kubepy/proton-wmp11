# proton-wmp11

```
cd ~
curl -LO https://web.archive.org/web/20190512112704/https://download.microsoft.com/download/3/0/8/3080C52C-2517-43DE-BDB4-B7EAFD88F084/wmp11-windowsxp-x64-enu.exe
```

```
cabextract wmp11-windowsxp-x64-enu.exe -d wmp11
```

```
PROTON_VERSION="Proton 9.0" protontricks -v 2191660 winxp
```

（Press Ctrl+C when the installer has finished， killall -9 "$PROG" script to kill the proton processes）
```
PROTON_VERSION="Proton 9.0" protontricks-launch --appid 2191660 wmp11/wmp11-64.exe

    PROTONCORE=(pv-bwrap pressure-vessel reaper explorer.exe rpcss.exe plugplay.exe services.exe svchost.exe winedevice.exe winedevice.exe wineserver)
    for PROG in "${PROTONCORE[@]}"; do
      killall -9 "$PROG"
    done

PROTON_VERSION="Proton 9.0" protontricks-launch --appid 2191660 wmp11/wmp11-64.exe

    PROTONCORE=(pv-bwrap pressure-vessel reaper explorer.exe rpcss.exe plugplay.exe services.exe svchost.exe winedevice.exe winedevice.exe wineserver)
    for PROG in "${PROTONCORE[@]}"; do
      killall -9 "$PROG"
    done
```

```
PROTON_VERSION="Proton 9.0" protontricks -v 2191660 win7
```
