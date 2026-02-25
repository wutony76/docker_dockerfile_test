# docker_dockerfile_test

docker Dockerfile 實驗.測試

$ docker build -t docker0225 .
$ docker images
使用 docker images 可以看到 docker0225 印象檔.
$ docker run -d -p 9200:80 --name TAG-docker0225 docker0225
