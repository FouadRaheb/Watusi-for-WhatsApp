## THIS IS ONLY FOR iOS 11.x - 11.1.2 ON ELECTRA JAILBREAK

```diff
- I'M NOT RESPONSIBLE IF YOU ENDUP LOSING YOUR DATA/JAILBREAK
- DO THIS AT YOUR OWN RESPONSIBILITY
- I HAVE TESTED THE SCRIPTS ON AN IPHONE 6S AND IPAD PRO 10.5
```

# Install tweaks from terminal

We need to ssh into the device first, you can do that from the device itself or via a mac/pc.

* If you're doing it via mac/pc, connect your idevice to the same Wi-Fi network and get its ip address from settings -> Wi-Fi -> information and then using a terminal run ```ssh root@ip_address```
* If you're doing it on your device, download iTerminal from AppStore and connect by using `127.0.0.1` as IP Address, `root` for username and `alpine` for password field.

1. Install WatusiTools

```
/bootstrap/usr/local/bin/wget -O - http://cydia.f0u4d.com/electra/com.f0u4d.watusitools/install.sh | /bootstrap/bin/bash
```

2. Install Watusi

```
/bootstrap/usr/local/bin/wget -O - http://cydia.f0u4d.com/electra/com.fouadraheb.watusi/install.sh | /bootstrap/bin/bash
```

### If you wish to remove the tweaks

Uninstall Watusi

```
/bootstrap/usr/local/bin/wget -O - http://cydia.f0u4d.com/electra/com.fouadraheb.watusi/remove.sh | /bootstrap/bin/bash
```

Uninstall WatusiTools

```
/bootstrap/usr/local/bin/wget -O - http://cydia.f0u4d.com/electra/com.f0u4d.watusitools/remove.sh | /bootstrap/bin/bash
```



# Installing tweaks manually

If you don't want to run the script above, you can just download and copy the files manually.

### Installing WatusiTools

##### Download .tar package from [here](http://cydia.f0u4d.com/electra/com.f0u4d.watusitools/package.tar) and extract it

* Copy `libWatusiTools.dylib` to `/usr/lib/libWatusiTools.dylib`
* Copy `FRToolsAssets.bundle` to `/bootstrap/Library/Application Support/WatusiTools/FRToolsAssets.bundle`


### Installing Watusi

##### Download .tar package from [here](http://cydia.f0u4d.com/electra/com.fouadraheb.watusi/package.tar) and extract it

* Copy `Watusi.dylib` to `/bootstrap/Library/SBInject/Watusi.dylib`
* Copy `Watusi.plist` to `/bootstrap/Library/SBInject/Watusi.plist`
* Copy `FRAssets.bundle` to `/bootstrap/Library/Application Support/Watusi/FRAssets.bundle`

### If you wish to remove the tweaks

#### Uninstall WatusiTools

* Delete `/bootstrap/Library/Application Support/WatusiTools/FRToolsAssets.bundle`
* Delete `/usr/lib/libWatusiTools.dylib`

#### Uninstall Watusi

* Delete `/bootstrap/Library/SBInject/Watusi.dylib`
* Delete `/bootstrap/Library/SBInject/Watusi.plist`
* Delete `/bootstrap/Library/Application Support/Watusi/FRToolsAssets.bundle`
