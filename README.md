# Introdution

## - A repository search for exact names

### This script search on the repository of apt and snap for packages,it need nala and snap for work.

```bash
sudo apt install nala snapd -y 
```

---

### After installing nala and snap download the repository and copy the file on /usr/local/bin,all the code of installation is into this line

- Install the script by only coping this line

```bash 
git clone https://github.com/Zmp0/repository-searcher.git && cd repository-searcher && sudo cp deb /usr/local/bin && sudo chmod +x /usr/local/bin/deb && sudo apt install nala snapd -y 
```

---

### After this you can search for any package from your repository

```bash
deb firefox
```

```bash
deb konsole
```

```bash
deb kde
```


### You can also install packages from snap and apt with the " -s " subcommand

```bash
deb -s firefox
```

```bash
deb -s konsole
```

```bash
deb -s kde
```
