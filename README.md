# trade_learn
trade doc &amp; learning notes



检查ssh是不是通了：
原文链接：https://www.cnblogs.com/olive27/p/6056612.html
最后一步：回到git bash 命令窗口，输入
ssh -T git@github.com
输入完成后出现上图中的内容，最后的yes是我自己输入的，也就是说你会看的的结尾是（yes/no）,你也跟着输入yes就好啦
出现红框中的文字就说明你成功啦，这时候你就可以任意的玩弄github啦，哈哈（pull和push啥的都可以了）。


git取消代理：
原文链接：https://blog.csdn.net/Hodors/article/details/103226958
我也记不清到底是第几次处理这种问题了failed to connect to github.com port 443
（1）取消代理
git config --global --unset http.proxy
git config --global --unset https.proxy
（2）获得成功！


git设置代理：
原文链接：https://blog.csdn.net/zpf1813763637/article/details/128340109
解决办法：配置http代理Windows、Linux、Mac OS 中 git 命令相同：
配置socks5代理
git config --global http.proxy socks5 127.0.0.1:7890
git config --global https.proxy socks5 127.0.0.1:7890
配置http代理
git config --global http.proxy 127.0.0.1:7890
git config --global https.proxy 127.0.0.1:7890

ls: start
