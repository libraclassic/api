# api

在 http://libraservice2.kulap.io/ 项目上优化而成 （原作者Nattapon Nimakul）

# Required
- node 10.15.3
- docker

# Config
- Open .evn
```
PORT=3000
HOST=localhost
AMOUNT_TO_MINT=100
DOCKER_IMAGE=kulap/libra_client:0.1
```

# install

```
sudo apt install docker.io
```

```
sudo service docker start
```

```
sudo gpasswd -a $(whoami) docker
```

```
npm install
```


# start

```
npm run start
```