My utils configurations for linux distros

Gnome isolate workspaces:
```bash
gsettings set org.gnome.shell.app-switcher current-workspace-only true
```

```bash
# mudar layout do teclado
setxkbmap -model abnt2 -layout br
```



Habilitar cancelamento de ruido microfone
```bash

# no ClearLinux
sudo nano /usr/share/pulseaudio/default.pa

# adicionar na última linha do arquivo
# modulo que habilita cancelamento de ruído
load-module module-echo-cancel

# reiniciar serviço
pulseaudio -k

```
