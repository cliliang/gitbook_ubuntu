### 下载器：
下载器使用xdman:
```
 sudo add-apt-repository ppa:noobslab/apps
 sudo apt-get update
 sudo apt-get install xdman
 //remove
 sudo apt-get remove xdmans
```

### sublime text 3
```
//download
wget https://download.sublimetext.com/sublime_text_3_build_3114_x64.tar.bz2
//zip
tar xvf sublime_text_3_build_3114_x64.tar.bz2
//cd进入sublime text 3的文件
./sublime_text
```
  为sublime安装package control后，安装emmet后，如果出现emmet的快捷键不起作用，是因为pyv8没有装好。这时可以正常通过[PyV8](https://github.com/emmetio/pyv8-binaries)下载。然后将下载的文件解压，重命名为“PyV8”，拷到’/home/cliliang/.config/sublie-text-3/Install Packages/‘下。再重新打开sublime即可。
  
### 软件的安装方法
一、Ubuntu中软件安装方法有以下几种方法
1.APT方式
. 普通安装：apt-get install softname1 softname2...
. 修复安装：apt-get -f install softname1 softname2...
. 重新安装：apt-get --reinstall install softname1 softname2..
2.dpkg方法
. 普通安装：dpkg -i pageagename.deb
3.源码安装(.tar、tar.gz、tar.bz2、tar.Z)