# Python Hello World Web App

这是一个简单的Python Flask Web应用程序，运行在Docker容器中，监听3000端口并返回"Hello World!"。

## 使用说明

### 方法1：使用Docker直接构建和运行

构建Docker镜像：
```bash
sudo docker build -t python-hello-world .
```

运行容器：
```bash
sudo docker run -p 3000:3000 python-hello-world
```

### 方法2：使用Docker Compose（推荐）

构建并运行：
```bash
docker-compose up --build
```

停止并删除容器：
```bash
docker-compose down
```

## 访问应用

运行后，在浏览器中访问 http://localhost:3000 查看"Hello World!"页面。
