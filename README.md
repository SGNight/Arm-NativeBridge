# Android x86 Arm NativeBridge (libhoudini)

Houdini is an ARM translation layer for android developed by Intel and Google to run ARM apps on x86 architecture.
The project is closed source and nowadays android x86 doesn't have it pre-installed in the system.
To enable ARM Native Bridge on android x86 you need to run the `enable_nativebridge` command from the terminal, which downloads the .sfs image file from the android x86 servers and runs the ARM activation commands according to your device architecture.

There are mainly 3 types of libhoudini used in android x86 :-

- houdini_7_x = (x86 arm translation)
- houdini_7_y = (x86_64 arm translation)
- houdini_7_z = (x86_64 arm64 translation)

Houdini files are named according to their android version :-

- Houdini_6 series =  android 6.0
- Houdini_7 series =  android 7.0
- Houdini_8 series =  android 8.0
- Houdini_9 series =  android 9.0

Houdini_6 series can be used in android 7.1 as well and the Houdini_8 series can be used in Android 9.0, but a higher version of Houdini is not compatible with the lower version of android.

# Download Links :- 

## Houdini_6 series
```
 http://dl.android-x86.org/houdini/6_x/houdini.sfs
 http://dl.android-x86.org/houdini/6_y/houdini.sfs
 http://dl.android-x86.org/houdini/6_z/houdini.sfs
```

## Houdini_7 series
```
 http://dl.android-x86.org/houdini/7_x/houdini.sfs
 http://dl.android-x86.org/houdini/7_y/houdini.sfs
 http://dl.android-x86.org/houdini/7_z/houdini.sfs
```

## Houdini_8 series
```
 http://dl.android-x86.org/houdini/8_x/houdini.sfs
 http://dl.android-x86.org/houdini/8_y/houdini.sfs
 http://dl.android-x86.org/houdini/8_z/houdini.sfs
```
## Houdini_9 series
```
 http://dl.android-x86.org/houdini/9_y/houdini.sfs 
```
# How to manually install Arm Native Bridge in android x86

- Download the required .sfs file from the above links.
- Rename the file houdini.sfs to houdini7_y.sfs
- Copy the houdini7_y.sfs file to /data/arm/ folder
- Do the same for the z series if you want to run the arm64 app.
- Press alt+f1 to open terminal & run the command `enable_nativebridge`.
- if you don't get any error msg then you've successfully activated ARM Native Bridge on your system.
- Press alt+f7 to return to GUI & download any game/app to test libhoudini.



