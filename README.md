<img width="90" height="90" src="imessage-icon.svg" alt="Apollo Icon" />

## Apollo

> 被精神分裂症（树苗嫁接）开发的通讯软件，功能完善，界面美观

<h3>   <a href="https://github.com/intelligent-long/Apollo/releases">下载</a> </h3>

## 部署
> 可直接使用中央服务器

### 依赖环境

| 组件 | 版本 |
|--------|--------|
| Java | 21+ |
| MySQL | 8.0+ |
| Redis | 7.0+ |
| MinIO | Latest |

### 部署流程
1. 安装 Java，兼容版本：Java 21
2. 安装 MySQL, Redis, MinIO
3. 解压服务端部署压缩包
4. 运行 `java -jar 程序文件.jar -dr` 获得部署文件，或者直接从压缩包得到部署文件
5. 在 MySQL 中创建数据库，执行 apollo.sql 文件，初始化数据库结构
6. 将 apollo-server-properties.json 文件复制到与 jar 文件同级目录，双击 jar 文件运行，填写内容，运行服务端。如果是命令行，填写 apollo-server-properties.json 内容，执行 `java -jar 程序文件.jar -cli apollo-server-properties.json` ，运行服务端
7. 安装客户端，连接服务端

## 代码

> 约 10 万行代码

## 特性

- 完善的功能
- 可自托管