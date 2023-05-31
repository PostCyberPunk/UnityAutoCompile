# Unity Auto Compile
this extesion will trigger Unity to compile when saved a file in VS Code.

### Requirement
Install this package to your projcet

### Known isssues
1. You have to force compile once before the auto-compilation works
2. If there is errors in Unity the auto Compile will stop

### Commands
Unity Force Compile: unity-auto-compile.compile
Toggle Unity Compilation :unity-auto-compile.toggle

### Extension Settings
```
unity-auto-compile.enabled
unity-auto-compile.port  //the HTTP port between unity and vscode
```
