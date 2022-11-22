# 本地开发常用组件Docker集成

### 获取Nginx默认配置

``` shell
docker run --name tmp-nginx-container -d nginx 

docker cp tmp-nginx-container:/etc/nginx/ ./nginx

docker rm -f tmp-nginx-container
```



