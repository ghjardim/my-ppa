## Installing the repo

```
curl -s --compressed "https://ghjardim.github.io/my_ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/my-ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/my-ppa.list "https://ghjardim.github.io/my-ppa/my-ppa.list"
```
