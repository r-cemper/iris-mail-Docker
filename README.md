# iris-mail-Docker
The original repo is lost, but the package survived in Docker and IPM      
### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory
```
$ git clone https://github.com/rcemper/DK_iris-mail.git
```
To build and start the container run:
```
$ docker compose up -d && docker compose logs -f
```
To open IRIS Terminal do:
```
$ docker-compose exec iris iris session iris
USER>
```
or using **iterm** in WebBrowser
```
http://localhost:42773/iterm/
```
To access IRIS System Management Portal
``` 
http://localhost:42773/csp/sys/UtilHome.csp
```
### How to use it
Some user documentation is found there in the [DC Article](https://community.intersystems.com/post/receive-mail-messages-iris-interoperability-production)  
Touch the [Interoperability Production here](http://localhost:42773/csp/user/EnsPortal.ProductionConfig.zen?PRODUCTION=dc.iris.mail.Production)
