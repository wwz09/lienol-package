#### 说明

* 软件不定期同步大神库更新，适合一键下载到package目录下，用于openwrt编译


1、 lede/package$下运行 或者openwrt/package$下运行


```bash
 git clone https://github.com/wwz09/lienol-package.git
```

 2、 或者添加下面代码到 openwrt 或lede源码根目录feeds.conf.default文件
 
```bash
 src-git wwz09 https://github.com/wwz09/lienol-package.git
```

 
 
- openwrt 固件编译自定义主题与软件
- luci-app-openclash       ------------------openclash图形         
- luci-app-advancedsetting ------------------系统高级设置
- luci-theme-ifit          ------------------透明主题（适配18.06修复主机名错误）
- luci-theme-atmaterial    ------------------atmaterial 三合一主题（适配18.06）     
- luci-app-aliddns         ------------------阿里云ddns
- luci-app-eqos            ------------------依IP地址限速
- luci-app-gost            ------------------隐蔽的https代理
- luci-app-adguardhome     ------------------去广告 
- luci-app-smartdns        ------------------smartdns防污染
- luci-theme-argon_new     ------------------二合蓝 紫主题
- luci-theme-opentomcat    ------------------修复主机名错误（适配18.06）  
- luci-theme-opentomato    ------------------修复主机名错误（适配18.06）





