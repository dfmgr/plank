## 👋 Welcome to plank 🚀  

   
  
  
### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf "https://github.com/dfmgr/installer/raw/main/install.sh")" && sudo dfmgr install installer
```

OR

### Automatic install/update  

```shell
dfmgr update plank
```
  
### requirements  
  
#### Debian based

```shell
apt install plank
```  

#### Fedora Based

```shell
yum install plank
```  

#### Arch Based

```shell
pacman -S plank
```  

#### MacOS  

```shell
brew install plank
```
  
#### Manual install  

  ```shell
APPDIR="$HOME/.local/share/CasjaysDev/dfmgr/plank"
mv -fv "$HOME/.config/plank" "$HOME/.config/plank.bak"
git clone https://github.com/dfmgr/plank "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/plank/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```

## Author  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ dfmgr: [Github](https://github.com/dfmgr) ⛵  

## Links

<p align=center>
   <a href="https://travis-ci.com/github/dfmgr/plank" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/dfmgr/plank.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/plank" target="_blank" rel="noopener noreferrer">plank wiki</a>  |  
  <a href="plank" target="_blank" rel="noopener noreferrer">plank site</a>
</p>  
