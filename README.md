# clash_mihome_config
clash/mihomo系列通用yaml（适用于openWRT-NIKKI插件及电脑端Mihome Party）

1.自用手搓版配置文件，引用自youtuber七尺宇大佬的教程《【全网最细】手搓yaml配置文件 | clash/mihomo系列通用、保姆级教程、让你彻底搞懂yaml文件》：https://www.youtube.com/watch?v=pm4aiZm17SU&t=1358s
相关文档为https://www.qichiyu.com/232.html
规则集仓库地址：https://github.com/MetaCubeX/meta-rules-dat/tree/meta

2.如果使用的是ImmortalWrt，需确保DHCP/DNS-常规-DNS 重定向选项处于关闭状态。原因是使用NIKKI插件进行透明代理时，DNS是由NIKKI直接劫持，而不需要像使用openclash时通过DNSMasq劫持。相关详细教程见七尺宇大佬的教程视频：https://www.youtube.com/watch?v=sl8zK0dv7iM，对应文档地址为：https://www.qichiyu.com/379.html

3.另一个可供参考的为安格视界大佬的教程《Mihomo（Nikki）一键完美配置 ：个性分流 + Clash 面板 + 机场聚合 + IPv6 + 回家，绝不手搓 + 绝无DNS泄露 + 绝无DNS污染，完美网络26》：https://www.youtube.com/watch?v=RsVX8n1FOVg
