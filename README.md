## Xray手动安装教程 https://github.com/chika0801/Xray-install

模板遵守以下标准：

- 缩进使用 4 个空格
- 方 (花) 括号不换行
- 对于 outbounds，客户端应有 proxy 和 direct，服务端应有 direct 和 block
- 除非是适用于特定场景的模板，否则应当将 geoip:private 路由到 direct 出站 (服务端配置路由到 block 出站)
- 除非是适用于特定场景的模板，否则配置文件中不应出现 DNS
- routing 中的 domainStrategy 保持默认，即 AsIs。

[感谢](https://github.com/v2fly/v2ray-examples)
