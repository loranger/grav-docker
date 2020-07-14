# grav-docker

In order to use [traefik as a docker reverse-proxy](https://computerz.solutions/docker-compose-traefik/), replace *__project__* with you project name

```shell
$ sed -i -e 's/project/myawesomegravproject/g' docker-compose.yml
```

and add it to you `/etc/hosts` file

```
127.0.0.1   myawesomegravproject.grav
```
