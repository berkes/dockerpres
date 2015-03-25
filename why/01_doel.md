!SLIDE center
#WHY
![why](why.gif)

!SLIDE bullets incremental
# Why
* Makkelijk te shippen
* Single Responsibility Principle
* Netwerken
* Onderhoud
* Dependencies

!SLIDE bullets incremental
# Shippen
* `docker pull ubuntu`
* `docker run apt-get install postgres`
* `docker run ...`
* `docker commit ubuntu:latest berkes/postgres`
* `docker push berkes/postgres`

!SLIDE bullets incremental
# Shippen 2
* `ssh example.com`
* `docker run berkes/postgres`

!SLIDE bullets incremental
# Netwerken
* `docker run -d --name db berkes/postgres`
* `docker run -d --name smtp berkes/mail`
* `docker run --link db:db --link smtp:smtp berkes/webapp`

!SLIDE bullets incremental
# Onderhoud
* Dockerfile
* Automatische builds

!SLIDE bullets incremental
# Dependencies
* Images containen alles
* Voortbouwen op andere images
