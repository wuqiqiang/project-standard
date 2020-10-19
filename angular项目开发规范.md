# angular 项目开发规范

## 环境准备
```
npm install -g @angular/cli
```

## 本地开发
```
// 开发目录
cd path-to-develop

// 安装依赖
npm i 

// 安装出问题执行如下操作
// package.lock.json // 删除
// npm cache clear --force // 清除npm缓存

// 启动开发模式
npm run start
// 部分需要设置配置变量
npm --project=project-name run start


```