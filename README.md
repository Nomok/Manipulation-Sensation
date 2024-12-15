# Manipulation Sensation

## Purpose
A really cool shader that lets you translate, scale, and rotate.

## Compiling:

### Requisites:
FXC (apart of the [Windows SDK](https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/))

### Windows: 
1. Insert `FXC.exe` into the root directory or insert the path for FXC in line 11 of `CompileShader.bat`
2. Run `CompileShader.bat`
3. You should get a successful compilation message:
```
fxc.exe "manipulationsensation.hlsl" /nologo /WX /Ges /Qstrip_reflect /Qstrip_debug /Tps_4_0 /Eps_main /Fo"manipulationsensation.fxc"
compilation object save succeeded; see Z:\Manipulation-Sensation\manipulationsensation.fxc
.
Shaders compiled ok
```

## TODO
- Fix to masking in overlay mode
- Android Support
- MacOS / IOS Support