# LabVIEW-Git-Setting
****Provide LabVIEW gitattributes and gitignore settings****

# For ".gitattributes", add
```
*.vi binary
*.vim binary
*.lvproj binary
*.lvclass binary
*.lvlps binary
*.aliases binary
*.lvlib binary
*.vit binary
*.ctl binary
*.ctt binary
*.xnode binary
*.xcontrol binary
*.rtm binary
```
# For ".gitignore", add
```
# Libraries
*.lvlibp
*.llb

# Shared objects (inc. Windows DLLs)
*.dll
*.so
*.so.*
*.dylib

# Executables
*.exe
*.rtexe

# Metadata
*.aliases
*.lvlps
.cache/

# builds
*/Builds/*
*/builds/*
Builds/*
builds/*
```
