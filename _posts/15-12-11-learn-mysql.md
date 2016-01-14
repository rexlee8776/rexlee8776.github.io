---
layout: post  
title: learn mysql
categories: [Blog ]  
tags: [learn ]  
description: it's a long long way 
---
#mysql基本操作命令

{% highlight shell %}
bin/mysql -u root -p PW -h localhost -P 3306
mysql -u root database < scripts.sql
mysqldump -u root database > scripts.sql
{% endhighlight %}

mysql> show databases;
mysql> use mysql;
mysql> show tables;
mysql> Grant all privileges on *.* to 'root'@'%' identified by ‘password’with grant option;
mysql> Grant all privileges on *.* to 'root'@'localhost' identified by ‘password’with grant option;
mysql> flush privileges;  (运行为句才生效，或者重启MySQL)


