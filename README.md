# Debian GNU/Linux Notes and Resources

This document lists common tasks after installing Debian GNU/Linux either with
or without a desktop environment.

## Basic Setup

Run the following commands to install and configure the basics:

```bash
su root
sed -i 's/main/main contrib non-free/' /etc/apt/sources.list
apt-get update; apt-get -y full-upgrade
apt-get install sudo vim ntp git tmux curl htop bmon build-essential apt-listbugs apt-listchanges netselect-apt
vim /etc/sudoers # Add your account with desired permissions
exit
```

Change the terminal edit mode:

```bash
cd ~
echo set editor-mode vi > .inputrc
```

## Packages

### Tools

* htop - Command line mornitor and task manager
* bmon (run bmon -b for bps)
* iostat
* tcpdump
* vim
* ntp
* build-essentals
* git
* apt-listbugs
* apt-listchanges
* guake
* tmux
* zsh
* mtr
* progress


### Internet

* Chrome
* Vivaldi
* youtube-dl


### Audio

* pithos
* musescore
* handbrake
* vlc


### Video

* flowblade
* openshot
* vlc


### Images

* inkscape
* gimp


### Productivity

* liferea
* bibletime
* virtualbox
* zim
* jitsi


### Programming

* Python3
* spyder (inc: matplotlib, pandas, numpy, sympy, scipy, scikit-learn)


### Games

* steam
* http://www.penguspy.com/
* freeciv








