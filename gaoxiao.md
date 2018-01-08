#对吉林大学某站的一次渗透测试
http://202.198.17.226:8088/oa/index.php
口令admin 000000 上传。

#物联网风险之看我如何远程打开清华大学的机房大门
http://166.111.9.20:802/View/Login.aspx 用户名存在注入，
直接使用admin'OR'a'='a/admin'OR'a'='a这时候点登录没有反应。然后在进入web根目录，就直接登录了。注入破解mysql密码，redis未授权访问。C段有个Mongodb未授权访问，hadoop未授权访问。\

#ofo共享单车SQL注入漏洞影响北京大学等多所高校共享车辆解锁密码及9万用户隐私
某处 api 没有对 SQL 注入过滤，导致后台密码，车辆密码，用户隐私泄露, www.ofo.so/Api/getPacket 红包页面没有对 SQL 注入过滤。