对angularjs封装


Change to your project's root directory.

```bash
git clone https://github.com/hlwen/hlwen-angular.git

npm intall 

node --harmony index.js
```



服务器配置参数 :
 "scripts": {
     "start": "http-server -a 0.0.0.0 -p 8000",
 }
-p 端口号 (默认 8080)

-a IP 地址 (默认 0.0.0.0)

-d 显示目录列表 (默认 'True')

-i 显示 autoIndex (默认 'True')

-e or --ext 如果没有提供默认的文件扩展名(默认 'html')

-s or --silent 禁止日志信息输出

--cors 启用 CORS via the Access-Control-Allow-Origin header

-o 在开始服务后打开浏览器

-h or --help 打印列表并退出

-c 为 cache-control max-age header 设置Cache time(秒) , e.g. -c10 for 10 seconds (defaults to '3600'). 禁用 caching, 则使用 -c-1.
