# Apt_t00ls
高危漏洞利用工具
---
泛微:  
e-cology workrelate_uploadOperation.jsp-RCE (默认写入冰蝎4.0.3aes)  
e-cology page_uploadOperation.jsp-RCE (暂未找到案例 仅供检测poc)  
e-cology BshServlet-RCE (可直接执行系统命令)  
e-cology WorkflowServiceXml-RCE (默认写入内存马 冰蝎子 3.0 beta11)  
e-office logo_UploadFile.php-RCE (默认写入冰蝎4.0.3aes)  
e-office10 OfficeServer.php-RCE (默认写入冰蝎4.0.3aes)  
e-mobile_6.6 messageType.do-SQlli (sqlmap利用，暂无直接shell的exp)  

用友:  
yongyou_chajet_rce (用友畅捷通T+ rce 默认写入哥斯拉 Cshap/Cshap_aes_base64)  

中间件:  
IIS_PUT_RCE (emm暂时没办法getshell  仅支持检测 java没有MOVE方法)  

安全设备:  
综合安防_applyCT_fastjson-RCE(仅支持检测,自行使用ladp服务利用)  

---
## 工具模块:  

文件上传指令生成  
<img width="962" alt="微信图片_20221002223437" src="https://user-images.githubusercontent.com/100954709/193459785-24f45480-764a-4d12-9fe8-485112bf4ef1.png">  

Tasklist敏感进程检测  
<img width="962" alt="微信图片_20221002223828" src="https://user-images.githubusercontent.com/100954709/193459855-71f0e49a-c6e5-44f9-800c-e0aae7e995f5.png">

---
## 配置相关  

部分漏洞使用dnslog检测  请自行修改 Apt_config/dnslog下内容  
本工具使用CEYE.IO   只需修改为自己的地址及tokent即可  

---
## 问题反馈
可直接提Issu 或加我wx进群交流  
  
![my](https://user-images.githubusercontent.com/100954709/193801691-df73fec6-284a-450a-943a-09fe023bcde0.png)  



