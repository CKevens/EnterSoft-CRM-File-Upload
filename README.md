# EnterSoft-CRM-File-Upload

## 产品简介 

- 浙大恩特CRM是由浙江大学恩智浙大科技有限公司推出的客户关系管理（CRM）系统。

## 影响版本：

- 浙大恩特CRM全版本

## 漏洞利用点：

<code>/entsoft/CustomerAction.entphone;.js?method=loadFile</code> 接口，当访问接口时出现如下响应体时，可认定该漏洞存在。

## EXP：

访问：<code>/url/enterdoc/gesnum/xxxxxx/photo/xxxx.jsp</code>

将poyload换成webshell马，可获取服务器权限。
