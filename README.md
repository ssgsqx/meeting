
`启动步骤`

1. git clone http://xxxxxx

2. npm install

3. npm start

4. npm run build:test 测试环境

5. npm run build:prod 生产环境

6. HTTPS=true npm start 使用 HTTPS 环境（共享桌面必须） 
`使用技术栈`


1. create-react-app + antd + axios

2. 拓展 webpack_config  --> customize-cra react-app-rewired 

3. add config-overrides.js ---> antd按需加载、使用less、配置antd 主题

4. 打包设置环境变量  dotenv-cli 包 + .env.test(测试环境变量)/.env.production(生产环境变量)




`基础版本`

    只有推拉流 和 人员流音视频状态显示