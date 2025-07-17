# configurer_une_VM_linux

### Procédure

```bash
dpkg-reconfigure keyboard-configuration
```

####Ensuite

```bash
nano /etc/default/keyboard
```

#### remplacer le contenu par
```bash
XKBMODEL="apple_laptop"
XKBLAYOUT="fr"
XKBVARIANT="mac"
XKBOPTIONS=""
BACKSPACE="guess"
```

#### enregistrer le fichier et quitter 

#### puis recharger la config sans redemarrer (ne pas appliquer sudo si en mode root)

```zsh
setupcon
dpkg-reconfigure keyboard-configuration
```





