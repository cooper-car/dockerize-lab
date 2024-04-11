```bash
// 建立image
docker build -t my-vue:1 .

// 啟動一個container
docker run -d -p 8080:8080 --name my-vue my-vue:1
```