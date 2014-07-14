Mangatux
======================

A project based in the Linux Manga downloader by Kurobyte, renewed, with some changes, bug corrections and, little by little, new features.

DEPENDENCIES:

To install the program and make it run you will need:
 ·wget
 ·gtkdialog
 ·zenity
 ·links
 ·libnotify
 
These dependencies are needed to download the manga and to show you the windows and notifications so it's important for you to install every one

INSTALLATION:

Ubuntu-Debian:
If you are using Debian, Ubuntu, or another Debian-based distro, soon you will have deb packages here to download, but by now, the only thing you have to do is to download the folder "usr" in the git repo and copy it directly in your system, with these commands on the terminal:
      
      cd ~
      
      git clone https://github.com/jorge-barroso/Mangatux.git
      
      cd Mangatux
      
      sudo cp -r ./usr/ /usr/
      
Fedora (RPM's):
You'll also have RPM packages as soon as possible tracking the daily development, by now you can also do the following steps:
      
      cd ~
      
      git clone https://github.com/jorge-barroso/Mangatux.git
      
      cd Mangatux
      
      sudo cp -r ./usr/ /usr/

Arch Linux:
The package is in the aur, you can install it by typing:
      
      yaourt -S mangatux

If you don't have yaourt already installed, you can install yaourt in the following steps:

Method 1:
 ·Open /etc/pacman.conf on your text editor as super user
 ·Go to the end of the file
 ·Add three lines:
      [archlinuxfr]
      SigLevel = Never
      Server = http://repo.archlinux.fr/$arch
 ·Then run the next command on your terminal:
      pacman -Sy yaourt

Method 2:
  ·Copy and paste the next commands in order to get it installed:
      curl -O https://aur.archlinux.org/packages/pa/package-query/package-query.tar.gz
      tar zxvf package-query.tar.gz
      cd package-query
      makepkg -si
      cd ..
      curl -O https://aur.archlinux.org/packages/ya/yaourt/yaourt.tar.gz
      tar zxvf yaourt.tar.gz
      cd yaourt
      makepkg -si
    
    
DEVELOPERS:
It would be great if you had any ideas to add to the project so if you want to callaborate write me on my email, do a pull request (if you have a github profile) or whatever you can do, I'll be glad to have your collaboration. To retrieve the fonts you know, just do:

      git clone https://github.com/jorge-barroso/Mangatux.git (simple HTTPS method)
        
      git clone git@github.com:jorge-barroso/Mangatux.git (If you have SSH Keyring)
        
      svn checkout https://github.com/jorge-barroso/Mangatux (Subversion)

With that you will get the sources to examinate them and make any suggestion that you want.
