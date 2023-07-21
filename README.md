 # ⚡ cs-1.6-docker ⚡

- Dependencies

    * [Docker](https://www.docker.com/)
    * [ZeroTier](https://www.zerotier.com/) `this only if you are outside of the LAN`

for millenials still playing this crap ;)

to run the server need install docker /\


run this command into your terminal
````
docker-compose up -d
docker-compose stop hlds
docker cp maps cs-dedicated-server:/hlds/cstrike/
````

# Spanish configs

para connectarse como cliente desde afuera de una LAN tienen que instalar zeroTier y pedierle a tu host
la red de zerotier y depues connectarse desde la ipconpuerto del zerotier

ejemplo `connect 192.168.195.19:27016`
/\ con esto ya te podrias connectarse al servidor


