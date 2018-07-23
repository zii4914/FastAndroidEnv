### git在windows上配置ssh公钥

配置git的user name和email：

$ git config --global user.name "lxyz" 

$ git config --global user.email "1129103472@qq.com"
  
### 生成密钥

ssh-keygen -t rsa -C “1129103472@qq.com”
 
按3个回车，密码为空。(第一次是配置输出key文件名称，默认即可，第二第三次为配置key的密码)

### 在Github或其他平台上配置添加ssh

到C:\Users\zii(电脑用户名)\.ssh下面将id_rsa.pub里的内容复制出来粘贴到对应平台的ssh配置页面中


>参考：  
>[Git官网](https://git-scm.com/book/zh/v1/%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E7%9A%84-Git-%E7%94%9F%E6%88%90-SSH-%E5%85%AC%E9%92%A5)