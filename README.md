# Windows

Edit `C:\Windows\System32\drivers\etc\hosts` and add these lines:

```
192.168.178.220 titan.sheehan.nz
192.168.178.221 jellyfin.sheehan.nz
192.168.178.222 jenkins.sheehan.nz
192.168.178.223 gitea.sheehan.nz
192.168.178.230 ganymede.sheehan.nz
192.168.178.231 jenkins-agent-alpha.sheehan.nz
```

# Linux

Edit `/etc/hosts` and add these lines:

```
192.168.178.220 titan.sheehan.nz
192.168.178.221 jellyfin.sheehan.nz
192.168.178.222 jenkins.sheehan.nz
192.168.178.223 gitea.sheehan.nz
192.168.178.230 ganymede.sheehan.nz
192.168.178.231 jenkins-agent-alpha.sheehan.nz
```

# NixOS

Edit `/etc/nixos/configuration.nix` and add these lines:

```
networking.extraHosts =
  ''
  192.168.178.220 titan.sheehan.nz
  192.168.178.221 jellyfin.sheehan.nz
  192.168.178.222 jenkins.sheehan.nz
  192.168.178.223 gitea.sheehan.nz
  192.168.178.230 ganymede.sheehan.nz
  192.168.178.231 jenkins-agent-alpha.sheehan.nz
  '';
```
