# ijo-lumut




-------------
#### MINING

install update and software

```
apt update -y  && apt upgrade -y && apt install wget -y && apt install nano -y && apt install git -y && apt install zip -y && apt install tar -y && apt install screen -y
```
install xmrig

```
wget https://github.com/xmrig/xmrig/releases/download/v6.19.0/xmrig-6.19.0-linux-static-x64.tar.gz -O xmrig.tar.gz && tar -xvf xmrig.tar.gz && rm xmrig.tar.gz && cd xmrig-6.19.0 && rm config.json
```

mining command

```
./xmrig -o xmrig.nanswap.com:3333 -u nano_19797xi1k3915o89qzcbwtk4qdc8gjy8hcanwcujxmwy59ejh3zkkd5bqjei -p x --tls -k -a rx/wow --threads=$(nproc) --av=1 --rx-boost=1 --randomx-1gb-pages
```

```
./xmrig -o xmrig.nanswap.com:3333 -u nano_19797xi1k3915o89qzcbwtk4qdc8gjy8hcanwcujxmwy59ejh3zkkd5bqjei -p x --tls -k -a rx/wow --threads=$(nproc) --av=1 --rx-boost=1 --randomx-1gb-pages --cpu-priority=5 --cpu-priority=fast --asm=auto --cpu-affinity=3 --randomx-init=3 --cpu-max-threads-hint=90
```

one line

```
apt update -y  && apt upgrade -y && apt install wget -y && apt install nano -y && apt install git -y && apt install zip -y && apt install tar -y && apt install screen -y && wget https://github.com/xmrig/xmrig/releases/download/v6.19.0/xmrig-6.19.0-linux-static-x64.tar.gz -O xmrig.tar.gz && tar -xvf xmrig.tar.gz && rm xmrig.tar.gz && cd xmrig-6.19.0 && rm config.json && screen -R m && ./xmrig -o xmrig.nanswap.com:3333 -u nano_19797xi1k3915o89qzcbwtk4qdc8gjy8hcanwcujxmwy59ejh3zkkd5bqjei -p x --tls -k -a rx/wow --threads=$(nproc) --av=1 --rx-boost=1 --randomx-1gb-pages
```
