build
```bash
docker build . -t ctnelson1997/cs571-f24-hw5-api
docker push ctnelson1997/cs571-f24-hw5-api
```

run
```bash
docker pull ctnelson1997/cs571-f24-hw5-api
docker run --name=cs571_f24_hw5_api -d --restart=always -p 48105:48105 -v /cs571/f24/hw5:/cs571 ctnelson1997/cs571-f24-hw5-api
```
