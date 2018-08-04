# How To Install
## Using dpkg
```
$ sudo dpkg -i ARToolKit_2.72.1_Ubuntu_amd64.deb
```

## Using gdebi
```
$ sudo apt install gdebi
$ sudo gdebi ARToolKit_2.72.1_Ubuntu_amd64.deb
```

# How to create deb package
```
dpkg-deb -b deb_project ARToolKit_2.72.1_hogehoge.deb
```
