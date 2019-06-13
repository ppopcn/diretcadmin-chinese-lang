# DirectAdmin 最新版 中文语言包  
  
我们从2007年开始提供DirectAdmin授权相关的服务  
语言包均为原创翻译  
原本仅提供给我们授权的客户内部使用的, 现在免费提供给公众客户使用

## 如果有需要购买DirectAdmin授权  
## 请在我们的官方网站[成立于2007年的主机软件官方网站购买](http://9181.taobao.com)


## 当前版本
* DirectAdmin 最新软件 版本  ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `1.55`  系列
* DirectAdmin 中文语言 版本  1.55 系列

  
 ![](directadmin.png)

  
## 安装教程1 Git方式
```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang
wget --no-check-certificate  -c https://github.com/ninetian/diretcadmin-chinese-lang/archive/1.501.zip
unzip 1.501.zip
rm -rf 1.501.zip
mv diretcadmin-chinese-lang-1.501 cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```



