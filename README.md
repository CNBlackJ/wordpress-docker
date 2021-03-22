# wordpress + docker-compose

## 前提条件

- 安装了`docker`
- 安装了`docker-compose`
- 有本地或云`mysql`

## 启动服务

- 复制配置文件
  - `cp .env_example .env`
- 修改配置文件参数
  - CONTAINER_NAME: 容器名称(可选)
  - MYSQL_HOST: mysql数据库的地址
  - MYSQL_PORT: 数据库端口(默认3306)
  - MYSQL_USER: 连接数据库的用户名
  - MYSQL_PASSWORD: 连接数据库的用户密码
  - MYSQL_DB: 数据库名
  - PORT: 服务对外暴露的端口
- 检查配置是否正确
  `docker-compose config`
- 启动
  - `docker-compose up`

## 使用&配置

参考详细的[文章](#https://zhuanlan.zhihu.com/p/34254509)
