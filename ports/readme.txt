port.yaml       my gogo portscan config add for ports files 

bounty.txt      用作工作、专项渗透，该列表包含了大部分可能出现漏洞的端口业务
bounty-top.txt  效率，用作批量
http.txt        记录了大部分 http 业务可能存在的端口
http-top.txt    效率，用作批量
brute.txt       测绘登录爆破业务
db.txt          测绘数据库业务
mail.txt        测绘邮件业务

区间包容：
bounty & http.txt > bounty-top.txt > http-top.txt & db.txt & mail.txt & brute.txt

get onliners ports such 80,8080,9090...
paste -sd, example.txt