# pop_vs_price
## Source code

Please see the file 'Pop. vs. Price LR 2.0.ipynb'.

## Docker hub link

https://hub.docker.com/r/rainite/pop_vs_price/

This docker has installed all of the required models and can execute on a built-in jupyter notebook.
You can simply type this command to create instance of the docker image with exposing port 8888, and then copy the jupyter link to browser.
```shell
docker run -it --rm -p 8888:8888 rainite/pop_vs_price
```
If you want to modify this docker, type these 2 set-up commands to run in root user.

```shell
docker run -ite  GRANT_SUDO=yes --rm -p 8888:8888 rainite/pop_vs_price 
```
```shell
docker exec -it --user root [CONTAINER ID] /bin/bash
```
