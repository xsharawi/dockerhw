# docker docker docker

repo serves an html index page and packs it up in a docker container 

and publishs itself into docker hub with github actions 

to run locally you can either

`docker pull xsharawi/nginxtest:latest`


or 

`git clone {this repo}`

`cd into-repo`

`docker compose up`

if you use `docker run` please note that you have to forward the port `80` for example `docker run -p 8080:80 xsharawi/nginxtest`
