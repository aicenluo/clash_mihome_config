更新于2025年3月6日
# clash_mihome_config
clash/mihomo系列通用yaml（适用于openWRT-NIKKI插件及电脑端Mihome Party）

1.自用手搓版配置文件，引用自youtuber七尺宇大佬的教程《【全网最细】手搓yaml配置文件 | clash/mihomo系列通用、保姆级教程、让你彻底搞懂yaml文件》：https://www.youtube.com/watch?v=pm4aiZm17SU&t=1358s
相关文档为https://www.qichiyu.com/232.html
规则集仓库地址：https://github.com/MetaCubeX/meta-rules-dat/tree/meta

不良林大佬3月19日又更新了教程《全网最细】手把手教你定制自己的yaml文件，mihomo/clash全平台通用，告别早已落后的订阅转换，机场订阅 | 自建节点 | 链式代理 | DNS泄露 | 二进制规则转换、等全介绍！》https://www.youtube.com/watch?v=eUqf3lOhFSw。
niki-clash-fallback是fallback策略，niki-clash-fallback-smart应用了smart策略。

2.如果使用的是ImmortalWrt，需确保DHCP/DNS-常规-DNS 重定向选项处于关闭状态。原因是使用NIKKI插件进行透明代理时，DNS是由NIKKI直接劫持，而不需要像使用openclash时通过DNSMasq劫持，为避免两者冲突，故需关闭。相关详细教程见七尺宇大佬的教程视频《全网最全】openwrt完美插件 nikki 喂饭级教程 | 插件安装卸载、各项设置以及注意事项讲解、各种使用方式讲解| openwrt mihomo | mihomotproxy》：https://www.youtube.com/watch?v=sl8zK0dv7iM
对应文档地址为：https://www.qichiyu.com/379.html

3.另一个可供参考的为安格视界大佬的教程《Mihomo（Nikki）一键完美配置 ：个性分流 + Clash 面板 + 机场聚合 + IPv6 + 回家，绝不手搓 + 绝无DNS泄露 + 绝无DNS污染，完美网络26》：https://www.youtube.com/watch?v=RsVX8n1FOVg
