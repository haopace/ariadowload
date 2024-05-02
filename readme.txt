#下载 aria2.sh & 安装 aria2
执行 aria2Install.py 脚本
python3 aria2Install.py
# 开启aria2
sudo su # 切换到root用户
# 执行aria2.sh脚本
sh ./pythonProject/aira/aria2.sh

# 4 启动aria2
# 转发6800端口
# 启动ariaNg
nginx -c /workspaces/131588624/pythonProject/nginx/nginx.conf
# 转发8888端口
# 替换aria2的配置文件，重启aria2
sudo cp /workspaces/131588624/pythonProject/aria/aria2.conf /root/.aria2c/aria2.conf
sudo echo 6|/workspaces/131588624/pythonProject/aria/aria2.sh
