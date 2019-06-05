# koxinga
A stern vector tile server that can work on Raspberry Pi - a part of rasv subproject

# [Document](https://hackmd.io/@hfu/koxinga)

# install (planned)
## install Docker (on Raspberry Pi)
```console
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo apt install docker-compose
```
thanks: [Raspberry PiでLet's EncryptなNginx Proxyを作ろう](https://qiita.com/Aruneko/items/0a6c0dd0fe1b8ede6cba)

## install koxinga
```console
git clone https://github.com/un-vector-tile-toolkit/koxinga
cd koxinga
docker build -t koxinga:latest .
```

# use (planned)
```console
docker run -ti --rm koxinga:latest bash
```
