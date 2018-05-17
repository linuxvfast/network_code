# network_code
网络编程代码
echo "# network_code" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/linuxvfast/network_code.git
git push -u origin master



目录结构
selectors_ftp 主目录
|
|_ _client
|        |_ _selectors_ftp_client.py 客户端启动文件
|_ _server
         |_ _selectors_ftp_server.py服务端启动文件
         
         
服务端启动 python3 selectors_ftp_server.py
客户端启动python3 selectors_ftp_client.py -s localhost -P9998
