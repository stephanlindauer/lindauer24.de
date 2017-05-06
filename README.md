# lindauer24.de

## Run development container
```
docker build -t bla . && \
docker run -p 80:80 \
  -v $(pwd)/html/:/usr/share/nginx/html/ 
  -v conf.d:/etc/nginx/conf.d
  bla
```
