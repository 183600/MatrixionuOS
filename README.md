# MatrixionuOS

 - This is the main repository for MatrixionuOS and is used as a guide for building MatrixionuOS
 - 一名初中生开发的Linux发行版，基于LingmoOS，一些信息没有修改，原QingmengOS，欢迎加Q群1020613301
 - A Linux distro developed by a junior school student, based on LingmoOS, originally QingmengOS. Welcome to QQ group 1020613301
 - [QQ群](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=kJnM0j24CHslZW-8eYDgilP0dvz0VV5L&authKey=EDmp6ct3Eu4IDQbliCA4I4FLXsJH6tP%2F9Q1rn%2BlI8dMiZPsjKCKejfLsW7u3mwyT&noverify=0&group_code=1020613301)(1020613301)
 - [Discord](https://discord.gg/JF3kHjjWTZ)
 - [云湖群](https://yhfx.jwznb.com/share?key=HnIJAmeafFkr&ts=1736527624)

# Preparations
## Build Host Requirements

 - Debian GNU/Linux 12(Bookworm), 13(Trixie) or later.
 - Disk free space > 50GB
 - Multi-core multi-threaded processor
 - 8 GB minimum running memory

## Tool preparation

### Clone This Code Warehouse.
   ```bash
   git clone https://github.com/183600/MatrixionuOS.git
   mkdir -p ~/bin
   cp -v MatrixionuOS/repo ~/bin/
   chmod a+x ~/bin/repo
   echo 'export PATH="$PATH:$HOME/bin"' >> ~/.bashrc
   source ~/.bashrc
```

# Initialize repo warehouse

## Create a directory for building:
```bash
mkdir -p workdir
cd workdir
```
## Init Repo

```bash
repo init -u https://github.com/183600/matrixionu-manifest.git -m manifest.xml
```

# Synchronization code
```bash
repo sync
```
