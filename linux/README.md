# debian repo

This is a debpository for my projects, mostly made for support with Debian (>=10). Use it by using the following:

```sh
curl -s --compressed "https://bashelled.github.io/deb/linux/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/bashelled.list "https://bashelled.github.io/deb/linux/listfile.list"
sudo apt update
```
