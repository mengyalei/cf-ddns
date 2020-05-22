# cf-ddns
1.下载cf自动更新DDNS解析脚本
<code>wget -N --no-check-certificate https://raw.githubusercontent.com/mengyalei/cf-ddns/master/cf-ddns.sh && chmod +x cf-ddns.sh </code>

2.添加定时  <code>crontab -e</code><br>
<code>*/3 * * * *  bash /root/cf-ddns.sh >/dev/null 2>&1 </code>
