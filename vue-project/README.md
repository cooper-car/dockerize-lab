
### dockerfile_perserve/dockerfile..0
```bash
// 建立image
docker build -t my-vue:1 .

// 啟動一個container
docker run -d -p 8080:8080 --name my-vue my-vue:1
```


### dockerfile_perserve/dockerfile.1
```bash
// 建立image
docker build -t my-vue:1 .

// 啟動一個container
docker run -d -p 8080:80 --name my-vue my-vue:1
```