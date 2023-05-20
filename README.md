```
apt-get install screen
```

```
screen -R vps
```

```
echo 1 > /proc/sys/net/ipv6/conf/all/disable_ipv6 && apt update -y && apt upgrade -y && apt install curl -y && apt install wget -y && wget https://raw.githubusercontent.com/ibnufachrizal/autoscriptku/main/setup.sh && chmod +x setup.sh && ./setup.sh && rm -rf setup.sh
```
