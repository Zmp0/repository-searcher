# Introdution

## - A repository search for exact names

### This script search on the repository of apt and snap for packages,it need nala and snap for work,so first of all 

```bash
sudo apt install nala snapd -y 
```

---

### After installing nala and snap download the repository and copy the file on /usr/local/bin

```bash 
git clone https://github.com/Zmp0/repository-searcher.git && cd repository-searcher && sudo cp deb /usr/local/bin && chmod +x /usr/local/bin/deb
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
