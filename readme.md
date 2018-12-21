项目patch列表（文件命名规则：patch编码-基准commit的id-项目名称）
1:深信服公安一聚项目（0001-f646b796923b843e6c3f2aa3508e660c10855c20-sxfgays）
   1.1 登录认证部分修改，由原来的LDAP认证，改为到VPN服务器认证，认证参数为用户id和浏览器传过来的token
   1.2 数据同步部分修改，主要修改import.helper.js中的toDepartmentEntity和toUserEntity两个函数
   1.3 lib/ldap/adlib.js中_search函数中的过滤条件部分
