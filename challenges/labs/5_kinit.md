```
[root@ip-172-31-53-128 ~]# kinit kang@AG35.FNG
Password for kang@AG35.FNG:
[root@ip-172-31-53-128 ~]# klist
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: kang@AG35.FNG

Valid starting     Expires            Service principal
11/14/16 23:09:33  11/15/16 23:09:33  krbtgt/AG35.FNG@AG35.FNG
        renew until 11/21/16 23:09:33

[root@ip-172-31-53-128 ~]# kinit kodos@AG35.FNG
Password for kodos@AG35.FNG:
[root@ip-172-31-53-128 ~]# klist
Ticket cache: FILE:/tmp/krb5cc_0
Default principal: kodos@AG35.FNG

Valid starting     Expires            Service principal
11/14/16 23:10:22  11/15/16 23:10:22  krbtgt/AG35.FNG@AG35.FNG
        renew until 11/21/16 23:10:22
```
