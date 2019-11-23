# squid-docker-compose

Squid proxy on Docker

# install

```
git clone https://github.com/thr3a/squid-docker-compose.git
cd squid-docker-compose
cp .env.sample .env

# change default username and password
vim Dockerfile

docker-compose up

# confirm
curl example.com localhost:3128
```
