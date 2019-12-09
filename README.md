# nodejs 模版

### 开发环境

- 代码编辑器: [vscode](https://code.visualstudio.com/)（其他文本编辑器也行）
- 辅助插件: editorconfig （根据.editorconfig 文件配置编辑器格式）eslint prettier
- 运行环境: [nodejs](https://nodejs.org)v10
- 依赖包管理工具: [npm](https://www.npmjs.com/)/[cnpm](https://npm.taobao.org/)（其他镜像也行）/[yarn](https://yarn.bootcss.com/)
- 代码管理工具: [Git](https://git-scm.com/)

### 使用

注入依赖

```sh
yarn install
```

开发

```sh
npm start
```

检查代码格式

```sh
npm run eslint
```

检查暂存区的代码格式

```sh
npm run lint-staged
```

修复代码格式

```sh
npm run fix
```

### 技术栈

- [Nodejs](http://nodejs.cn/): 构建语言基础
- [typescript](http://www.typescriptlang.org/): js 语言类型

### 集成工具

- Cz: 规范 git 提交说明(适配器, 自定义适配器, 说明校验, Angular 校验规范)
- ts-node: node 运行 ts
- eslint: 规范代码(ts 代码校验规则, prettier 代码美化工具)
- husky: git 钩子

### 项目目录

```text
.
├── app/                                           // 项目目录
│    └── index.ts                                  // 程序入口
├── node_modules/                                  // 依赖包
├── .commitlintrc.js                               // git提交说明规则配置
├── .cz-config.js                                  // cz自定义适配器配置
├── .editorconfig                                  // 编辑器基本设置
├── .eslintignore                                  // eslint代码检测忽略文件
├── .eslintrc.js                                   // eslint代码检配置
├── .gitignore                                     // git忽略配置
├── .prettierrc.js                                 // 代码美化工具配置
├── package.json                                   // 项目配置
├── README.md                                      // 说明
├── tsconfig.json                                  // ts配置
└── yarn.lock                                      // yarn依赖包版本锁定
```
