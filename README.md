# CrossTheWall（科学上网）

## Tutorials（教程）

- [x] 服务器被墙，依然可以科学上网，参考：[拯救被墙的 IP，CDN + v2ray，安全的科学上网方法](https://blog.sprov.xyz/2019/03/11/cdn-v2ray-safe-proxy/)

- [x] 在上面的基础上优化，自己指定 CDN 节点，可以让科学上网网速更快（自测带宽提到 10M +），参考：[V2Ray 拒绝减速 CDN，自选香港日本 CDN 节点让被墙 IP 起飞](https://www.youtube.com/playlist?list=PLEr-upeZHUno1NzE6XpjlVpTCkfdRZS05)

- [x] 在上面的基础上优化，自定义 v2ray 端口，把 80 端口让出来，交给 Nginx，然后由 Nginx 转发给 v2ray，这样服务器 80 端口可以用来放 web 项目，v2-ui 的网址也可以通过域名访问，参考：[这里](./v2ray/v2ray-nginx.md)

- [ ] 引入 https 和 http2（配置文件[戳这](./v2ray/v2ray-nginx-https-http2/)）

## 用户篇

- [v2ray+Cloudflare 用户修复指南](./v2ray-cloudflare.md)
## CDN 节点

- [Cloudflare 自定义 IP 节点收录](https://ofvps.com/201907510)

  - [中国移动推荐节点](./cloudflareNodes/chinaMobile.txt)

    - [上海移动亲测节点](./cloudflareNodes/chinaMobile-shangHai-tested.txt)

  - [中国电信推荐节点](./cloudflareNodes/chinaTelecom.txt)

## VPS

- 最便宜的 [Virmach](https://billing.virmach.com/cart.php?gid=18)

- 可以在同一台机器上免费切换 ip 的 [Hostwinds](https://www.hostwinds.com/vps/unmanaged-linux)

## [v2ray 配置模版](https://github.com/veekxt/v2ray-template)
