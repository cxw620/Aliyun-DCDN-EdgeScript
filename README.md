# Aliyun-DCDN-EdgeScript
## 自用阿里云DCDN边缘脚本(EdgeScript, ES)
- ### 阿里云DCDN边缘脚本介绍
	-  利用好阿里云DCDN的边缘脚本(ES)功能, 可以以最低成本做到:
		-  部分`SCDN`功能
			-  拦截大多数来源于IDC的访问
			-  拦截特定国家的访问
			-  拦截部分代理访问
			-  根据UA的拦截(不受CDN服务商常规的数量限制)
		-  利用`CDN鉴权`保护API不被非法访问
			- **无需**后端鉴权服务器
			- **无需**修改服务端代码
		-  `307跳转`分流
		-  IP Info API
		-  ...
-  ### 本仓库已有的实例
	-  基础安全规则
	-  `307跳转`分流 + `CDN鉴权`保护API(Bilibili Roaming API)
	-  IP Info API
