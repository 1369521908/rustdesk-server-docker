# rustdesk-server-docker
rustdesk-server docker deploy

# 该项目为rustdesk-server项目的docker部署项目 使用docker-compose进行部署

# 修改.env文件

+ RELAY_SERVER_IP 字段为服务器的 IP 地址
+ REGISTERED_EMAIL 字段为注册邮箱

# 启动
docker-compose up -d

# 查看日志
docker-compose logs -f