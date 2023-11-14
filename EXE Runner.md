# running exes on the vm
# Things to copy and paste:

```
sudo apt-get install wine
sudo apt-get install wine32
sudo apt-get install libwine
sudo dpkg --add-architecture i386
sudo mkdir -pm755 /etc/apt/keyrings
sudo wget -O /etc/apt/keyrings/winehq-archive.key https://dl.winehq.org/wine-builds/winehq.key
sudo wget -NP /etc/apt/sources.list.d/ https://dl.winehq.org/wine-builds/ubuntu/dists/mantic/winehq-mantic.sources
sudo apt update
sudo apt install --install-recommends winehq-stable
```

if all of that dont work here is a video on how to install wine
https://www.youtube.com/watch?v=i_B0d1f_2Hw

if it do work wine is installed double click on the exe in the file manager and click o run with wine
