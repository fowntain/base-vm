![image](https://user-images.githubusercontent.com/97373683/166140965-d63970e1-e4e5-41d1-b0e0-5833ba3b1ab9.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
# &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Chromebook-VM
### Initially made by jun-ro and expanded upon by fowntain


## Initial Setup
***You need a github account for this.***
---------------
**GitPod**

```
1. First go to https://gitpod.io and sign in with github


2. Then make a workspace with a new repo (perferably an existing one in your github account.)

Now follow the instructions below.
```
---------------
**GitHub Codespaces**
```
1. First go to https://github.com and make sure you're signed in
2. Fork this repository
3. Click the green code dropdown and click the codespaces tab
4. Click the + icon

Now follow the instructions below.
```

# Open the Terminal like this:
![image](https://user-images.githubusercontent.com/97373683/166133162-b45bbcf0-4431-4a85-b51f-4339f21ac3b9.png)



# Copy and paste this line in the terminal:
```
docker run --rm -d -p 3443:80 -v $PWD:/workspace:rw -e USER=username -e PASSWORD=Skool -e RESOLUTION=1366x650 --name ubuntu-SkoolVM fredblgr/ubuntu-novnc:20.04
```
### Like this: 
![Gif](https://gyazo.com/a8d59c59501b3f04d2fba0344b0c408d.gif)

Then click on "Open Window" as seen in this image
<br>
![Image](https://cdn.discordapp.com/attachments/741533658674102352/970189978070052946/unknown.png)
<br>
and enjoy!





# For Ubuntu/Linux Beginners

### First you want to install everything needed.
Copy these lines:

```
sudo apt-get update
sudo apt-get install neovim
sudo apt-get install terminator
```

### That should get you a basic text editor with a better terminal setup.
<br>



# Conlusion:
This VM is not perfect and can have major issues such as running a DE(Desktop Environment) but I think it's still capable of watching youtube videos and getting rid of pesky internet blocks.

<br>

# Credits:
https://github.com/jun-ro/Chromebook-VM
- Initial idea and tutorial
I expanded on this tutorial so I didn't completely rip it


# Bonus:
# [Minecraft](./Minecraft.md)
