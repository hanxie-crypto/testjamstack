## Serverless Devs 创建高性能Web站点演示
### 前置条件
安装好 serverless 命令行工具
```
npm i @serverless-devs/s -g
```
### 创建部署
+ 通过任意通用前端脚手架（create-react-app）创建前端应用
+ 通过 ***s cli init*** 指令初始化 配置脚本
+ 通过 ***s deploy*** 执行站点部署
+ 查看部署站点网址，进行测速

### 持续集成
+ 通过 ***s cli cicd*** 初始化部署脚本
+ 创建git项目并配置好阿里云秘钥信息
+ 代码提交查看构建效果
