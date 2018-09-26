#查看那些进程监听了哪些端口
    sudo lsof -i -P -n | grep LISTEN 
    sudo netstat -tulpn | grep LISTEN
    sudo nmap -sTU -O IP-address-Here
