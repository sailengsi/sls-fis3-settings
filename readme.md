# 百度fis3自动化工具常用配置 #

    git clone https://github.com/sailengsi/sls-fis3-settings
	cd fis3-settings/src/dev
	npm install
	npm run build
	npm start
	npm run dev


npn install		安装依赖

npm run build	编译dev目录中的内容，会在dev同级目录中生成release目录

npm run start	fis3内置server启动默认浏览器，访问编译生成的release目录

npm run dev		开启监听模式，在修改dev目录中的内容时，会自动编译并且刷新浏览器
