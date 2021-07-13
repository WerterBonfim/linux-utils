## 
### Nemo - VS code in context menu

```txt
in ~/.local/share/nemo/actions create vscode.action
```

```bash
[Nemo Action]
Name=Open in VS Code
Comment=Open in VS Code
Exec=code %F
Icon-Name=com.visualstudio.code
Selection=Any
Extensions=dir;
```
