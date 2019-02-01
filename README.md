# manjaro
manjaro tips and software list


#### software list

* database: datagrip
* redis: redis-desktop-manager
* mongo: robot3T,studio3T
* ide: idea, vscode
* global proxy: proxychain
* navigator: synapse
* cloud repo: dropbox
* markdown: typora
* pm: yay
* sh: zsh
* ftp: filezilla
* recompile: jd-gui
* gw: shadowsocks-qt5
* version: git
* zk: exhibitor
* kafka: kafka-manager
* container: docker
  
#### basic settings

*mirror*
```
sudo pacman-mirrors -i -c China -m rank
sudo pacman -Syyu
```

*pacman*
```
sudo vim /etc/pacman.conf
```
```
[archlinuxcn]
SigLevel = Optional TrustedOnly
Server = https://mirrors.ustc.edu.cn/archlinuxcn/$arch
```
```
sudo pacman -Syy && sudo pacman -S archlinuxcn-keyring
```

#### proxychains

#### yay
*install*
```
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```
*usage*
```
yay -S <package-name> # install some package

yay -Ss <package-name> # search some package in official repository

yay -Si <package-name> # view package information

yay -Syu # update all packages

yay <package-name> # shows menus of package

yay -Yc # remove unwanted dependencies
```


