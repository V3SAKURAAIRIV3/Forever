
♦️ For Debian 10 Only Digital Ocean recommended<br>
 
  ```html
 apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
  ```
♦️ For Ubuntu 20.04 Only Digital Ocean recommended<br>
  
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```
♦️ Installation <br>

  ```html
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/V3SAKURAAIRIV3/Forever/main/setup.sh && chmod +x setup.sh && ./setup.sh
  ```
  
