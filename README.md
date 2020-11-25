bash <(curl -Ls https://raw.githubusercontent.com/czjesda/v2ray-ws-tls/master/vless_tcp_xtls.sh)

1、使用SSH工具连接VPS，执行下列命令，选择安装v2ray+ws+tls

curl -O https://raw.githubusercontent.com/czjesda/v2ray-ws-tls/master/v2ray_ws_tls.sh && chmod +x v2ray_ws_tls.sh && ./v2ray_ws_tls.sh

2、使用SSH工具连接VPS，执行下列命令，选择安装v2ray+ws+tls1.3

curl -O https://raw.githubusercontent.com/czjesda/v2ray-ws-tls/master/v2ray_ws_tls1.3.sh && chmod +x v2ray_ws_tls1.3.sh && ./v2ray_ws_tls1.3.sh

3、等待脚本执行，过程中会提示需要输入域名，输入解析到本VPS的域名，然后回车

4、安装伪站点

wget https://github.com/czjesda/v2ray-ws-tls/raw/master/web.zip

unzip web.zip
