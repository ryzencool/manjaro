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
  
#### proxychain 

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

yay <package-name> # shows menu of package

yay -Yc # remove unwanted dependencies
```


