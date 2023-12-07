爬取网站图标

为了导航自动获取书签图标而写
```
http://127.0.0.1:8080/getfavicon?u=https://github.com
```

```
docker run -d -p 8080:8080 -v /home/favicon:/home/favicon --name getfavicon hellohechang/getfavicon:latest
```