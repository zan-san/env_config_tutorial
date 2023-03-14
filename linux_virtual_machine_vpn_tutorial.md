# introduce
if you located in china. vpn is necessary. this tutorial will help you use vpn in Linux virtual machine and don`t need install additional software in your linux virtual machine, instand to use vpn on your Windows home machine. 
# 1. check your vpn proxy server ip and port
able vpn local area network mode
# 2. set you virtual machine Network connncet method in NAT mode
for example
![def](image/virtualbox_setting.png)

# 3. open virtual machine and set the porxy server ip and port 
for example  
![def](image/proxy_setting.png)

open /etc/profile, add this

export http_proxy=http://proxy_ip:port     #代表http代理

export https_proxy=http://proxy_ip:port  #代表https代理

export ftp_proxy=http://proxy_ip:port  #代表ftp代理



然后执行source /etc/profile 即可。


# 4. have fun :)
