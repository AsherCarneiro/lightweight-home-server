## Beginners Guide to Simple Home Server.
This guide will get you setup with your own simple and lightweight home server using [docker](https://youtu.be/_dfLOzuIg2o) and more.

### - Prerequisites
+ A machine with [Docker](https://www.docker.com/products/docker-desktop/) installed
+ A machine with Debian based [Distro](https://ubuntu.com/download/desktop) or if you have windows then you can use [wsl2](https://youtu.be/_fntjriRe48)
+ Basic knowledge of using the command line [bash](https://www.hostinger.com/tutorials/bash-scripting-tutorial)

### - Learn a little about how to use [ubuntu](https://youtu.be/BMGixkvJ-6w), you can use any debian based distro.

### - [Apps to install on server](www.example.com)

### - Once you have a Linux distro ready, Here are the steps:
+ Firstly we will install some updates by `sudo apt -y update ` and when we do this the system will ask us for our user password just give it
+ Now that we have installed important updates, we will be using something called [ssh](https://youtu.be/v45p_kJV9i4)
+ SSH gives us the power to use our server from anywhere on our home network, later I will list some programs to access our server remotely on windows, another linux machine, mac or even android phone.
+ Simply run `sudo apt-get install -y openssh-server` into terminal to use it, if you prefer another method take a look [here](https://youtu.be/Wlmne44M6fQ).
+ Now that it's done, we will be setting up a static ip on our server, here's a guide for ubuntu [desktop](https://youtu.be/goCzjWseVNU) and [ubuntu server](https://youtu.be/HCHuySHVPK4) follow that and you should have static ip working.
+ What's a Static IP you ask, when we have lot of devices on our home network, a [DHCP server](https://youtu.be/S43CFcpOZSI) assigns local ip addresses to many devices each time they connect and disconnect so that's known as dynamic ip allocation.
+ Well away with them BIG words, next we will be accessing our server over ssh (as god intented), dont forget to note down your static ip address alongside your username and password on a paper for later (if you forget).
+ Get to your Windows Computer, open `cmd` or even `powershell` works.
+ We will type `ssh yourusername@yourstaticiphere` here replace `yourusername` with the username you gave when you made installed your linux system, if you want to find it simply open a terminal on your server machine, it will look like [this](https://i.stack.imgur.com/IxOje.png), here `macet` is the username.
+ If youre confused regarding ssh try [this](https://youtu.be/JbMgOKlj5fE) @ 3:40

