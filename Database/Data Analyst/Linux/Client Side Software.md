>[!important] I am using Ubuntu, so all installation process will be about it.

## Office
**Gnome extentions**
```bash
sudo apt install gnome-shell-extensions
```
**Gnome tweaks**
```bash
sudo apt install gnome-tweaks
```
**Clipboard extension for Gnome.**
Awesome and comfortable **clipboard**. Easy to set up and work with:
[Link to the tutorial](https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator/blob/master/README.rst)
```bash
$ git clone https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator.git ~/.local/share/gnome-shell/extensions/clipboard-indicator@tudmotu.com
# Reboot your pc here
$ gnome-extensions enable clipboard-indicator@tudmotu.com
```
**Bitwarden**.
I consider it the best password manager I've had:
```bash
sudo snap install bitwarden
```
**1.1.1.1**.
Makes your internet goes fastaaaa. It just sets up without installation
- [Link to the Tutorial](https://developers.cloudflare.com/1.1.1.1/setup/linux/)

## Problem solving
**Closed lid isn't suspend the system**
- [Link to the tutorial](https://itsfoss.com/ubuntu-close-lid-suspend/#:~:text=You%20must%20make%20sure%20that,Ubuntu%20by%20closing%20the%20lid.) I used console way. **BUT** you don't have to use gksu to open text document. You can use nano, it will be easier:
```bash
sudo nano /etc/systemd/logind.conf
```