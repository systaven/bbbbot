# 使用 Koyeb 官方的 docker-compose runner
FROM koyeb/docker-compose

# 拷贝你的 compose 文件
COPY . /app

# 设置工作目录
WORKDIR /app

# 启动 docker compose
CMD ["docker-compose", "-f", "astrbot.yml", "up"]
