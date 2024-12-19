# Serv00-CF代码
1.修改自Serv00|ct8老王与yonggekkk安装脚本，支持一键三协议：vless-reality、vmess-ws(argo)、hysteria2。

主要增加reality协议默认支持 CF vless/trojan 节点的proxyip以及非标端口的优选反代IP功能

Serv00专用一键脚本：
```
bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/Cloudflare_vless_trojan/main/serv00_proxyip.sh)\

主面板介绍
![image](https://github.com/user-attachments/assets/54f33785-9cf7-4271-9817-5d6cb9dc4623)

多账号进程保活脚本：
'''
curl -sSL https://raw.githubusercontent.com/yonggekkk/Cloudflare_vless_trojan/main/kp.sh -o kp.sh && chmod +x kp.sh && nano kp.sh
'''
https://raw.githubusercontent.com/your-username/your-repository/main/kp.sh


多账号进程保活脚本已支持，把kp.sh文件放到第三方VPS服务器，修改里面的参数即可定时自动运行保活节点

Serv00保活脚本，默认nano编辑形式，参数添加完毕运行bash kp.sh即可

curl -sSL https://raw.githubusercontent.com/yonggekkk/Cloudflare_vless_trojan/main/kp.sh -o kp.sh && chmod +x kp.sh && nano kp.sh
2、VPS专用：
