# Chromium on docker
A docker container which run chromium on your browser with selected port and credentials.

## Installation
Clone the repo:

```
git clone https://github.com/ali-avani/docker-chromium.git
cd docker-chromium
```

Edit configuration:
```
cp .env.sample .env
vim .env
```
Run docker:
```
docker compose up -d
```
Open browser and insert link:
http://[IP OR DOMIAN]:[PORT]
