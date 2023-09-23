# execrypt
Encrypted shell script concept

Deps:
- [ccrypt](https://ccrypt.sourceforge.net)
- [zenity](https://help.gnome.org/users/zenity/stable)

How it works:
- "secret.sh" <- my secret shell script
- secret.sh -> [ccencrypt](https://ccrypt.sourceforge.net) -> secret.sh.cpt
- ```execrypt secret.sh.cpt``` -> password -> decrypt and exec

# Installation
```sudo curl -sSL https://raw.githubusercontent.com/Raais/execrypt/main/execrypt -o /usr/local/bin/execrypt && sudo chmod a+x /usr/local/bin/execrypt```