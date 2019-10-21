# electron-with-create-react-app

> 整合 Electron 与 React.js (create-react-app) 的工程模板，支持一键启动 dev 模式与打包

## 开发模式

```sh
# 安装依赖
npm install

# 开发模式 
npm run dev
```

## 构建打包

```sh
# 全局安装 electron-builder
npm -i -g electron-builder

# 首先构建 React
npm run build:react

# 构建 electron 可执行文件
npm run build:electron
```

## 参考教程

- [Building an Electron application with create-react-app](https://www.freecodecamp.org/news/building-an-electron-application-with-create-react-app-97945861647c/)
- [Electron.js 快速入坑指南 - Windows 下的打包](https://canwdev.gitee.io/manual/setup-electronjs.html#windows-%E4%B8%8B%E7%9A%84%E6%89%93%E5%8C%85)
