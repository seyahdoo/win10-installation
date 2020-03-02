# Windows 10 LTSB Installation (cleanest win 10 ever)


1- [download](https://www.reddit.com/r/Piracy/comments/9kw6ff/windows_10_ltsc_2019_x64_en_iso/) win 10 ltsb iso
```
name: en_windows_10_enterprise_ltsc_2019_x64_dvd_74865958.iso
size: 3878287360 bytes (3698 MiB)
sha1: 0B8476EFF31F957590ADE6FE671F16161037D3F6
```


2- setup flash drive for installation using [rufus](https://github.com/pbatard/rufus/releases/download/v3.9/rufus-3.9p.exe)
```
partition scheme: GPT
target system: UEFI
file system: Large FAT32
```

3- boot from flash drive and install normal (not the N) version

4- disable win 10 anti virus program using group policy, open gpedit.msc and appy below settings
```
Computer Configuration > Administrative Templates > Windows Components > Windows Defender Antivirus > Turn off Windows Defender Antivirus > Enabled
Computer Configuration > Administrative Templates > Windows Components > Windows Defender Antivirus > Real-time Protection > Turn on behavior monitoring > Disabled 
Computer Configuration > Administrative Templates > Windows Components > Windows Defender Antivirus > Real-time Protection > Monitor file and program activity on your computer > Disabled 
Computer Configuration > Administrative Templates > Windows Components > Windows Defender Antivirus > Real-time Protection > Turn on process scanning whenever real-time protection is enabled > Disabled 
```

5- install [firefox](https://www.mozilla.org/en-US/firefox/download/thanks/)

6- uninstall internet explorer
```
go to "turn windows features on or off" using start menu search function
untick "Internet Explorer 11"
press ok, then restart
```

7- install [mpc-hc](https://mpc-hc.org/)

8- uninstall windows media player
```
go to "turn windows features on or off" using start menu search function
untick "Windows Media Player inside Media Features"
press ok, then restart
```
9- (optional) use program in this [link](https://github.com/CHEF-KOCH/HWIDGEN-SRC/raw/master/src/externals/hwid.kms38.gen.mk6.exe) in KMS38 mode as a dirty little pirate

