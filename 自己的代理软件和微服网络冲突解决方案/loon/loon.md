# loon

***此为手机版本的配置***


点击配置文件，在 [General] 部分做如下修改：

skip-proxy后面加 ",*.heiyu.space, *.lazycat.cloud" (加引号内的内容)
bypass-tun后面加 ",6.6.6.6/32, 2000::6666/128" (加引号内的内容)

新增如下内容，如果已经配置过 real-ip，就直接追加 `=` 后面的部分：

real-ip = *.heiyu.space, *.lazycat.cloud

