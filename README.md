<p align="center">
  <img height="100px" src="./logo.jpeg" />
</p>

# [Pagekit](https://github.com/pagekit/pagekit)

Pagekit是一个模块化的简单轻量内容管理系统。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Pagekit&branch=master)
### 配置
- `DB_TYPE`：数据库类型
- `DB_HOST`：数据库地址
- `DB_NAME`：数据库名
- `DB_PORT`：数据库端口号
- `DB_USER`：数据库用户名
- `DB_PASS`：数据库密码
- `ADMIN_USER`：管理员账户名
- `ADMIN_PASSWORD`：管理员账户密码
- `PORT`：应用端口号

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

