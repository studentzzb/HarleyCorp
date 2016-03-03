# open api demo (java ver.)
java version "1.7.0_75"

## Getting Started

1..将工程clone到本地：```git clone https://github.com/ddtalk/HarleyCorp.git```，导入到IDE中，比如eclipse点击```File->import```导入到eclipse中

2.打开工程的Env.java文件，填入企业的CORP_ID和SECRET（CORP_ID和SECRET可以在企业OA后台找到）
```
    public static final String CORP_ID = "";
    
    public static final String SECRET = "";
```
![corp](https://img.alicdn.com/tps/TB1oZwOKFXXXXc1XVXXXXXXXXXX-1084-621.jpg)

3.部署工程

4.OA后台创建微应用，并把工程的首页地址填到微应用首页中。
[如何创建微应用？](http://ddtalk.github.io/dingTalkDoc/#step-2-创建微应用)

![mico](https://img.alicdn.com/tps/TB1N490JFXXXXceXFXXXXXXXXXX-602-524.png)

###本DEMO具体实现

1.jsapi权限验证配置流程

请查看[文档](http://ddtalk.github.io/dingTalkDoc/#页面引入js文件)
- 前端文件:WebContent/index.jsp，WebContent/javascripts/demo.js
- 后端文件:[链接](https://github.com/injekt/openapi-demo-java/blob/master/src/com/alibaba/dingtalk/openapi/demo/auth/AuthHelper.java)

2.免登流程

请查看[文档](http://ddtalk.github.io/dingTalkDoc/#手机客户端微应用中调用免登)
- 前端文件:WebContent/javascripts/demo.js和
- 后端文件:[链接](https://github.com/injekt/openapi-demo-java/blob/master/src/com/alibaba/dingtalk/openapi/servlet/UserInfoServlet.java)



