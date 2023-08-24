# d2-crud-plus与d2-admin集成启动项目

## 修改之处
1. `main.js` import `'./busienss'`
2. `business/index.js` 进行`d2-crud-plus`的初始化工作
3. 请求返回结果去掉`.data`，将`{code,msg,data}`整体传递到下层
4. `views/demo` 为示例页面


## 带权限版本
请checkout permission分支


git地址：https://gitee.com/liqianglog/django-vue-admin?_from=gitee_search
git 代码：git@gitee.com:liqianglog/django-vue-admin.git
演示地址：http://demo.django-vue-admin.com
	账号：superadmin  	密码：admin123456
文档地址：https://django-vue-admin.com

接口：ApiPost7=》登录=》企业级后台管理系统