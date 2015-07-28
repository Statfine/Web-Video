# Web-Video
H5 播放器

移动端浏览器大部分是禁用video和audio的autoplay功能
并且，很多移动浏览器也不支持首次js调用play方法进行播放（只有用户手动点播放后暂停，然后用代码进行play可以）。
这样做主要是为了防止不必要的自动播放浪费流量
大多数移动端浏览器强制只要交互过一次后才能通过代码控制播放，无法强制，是浏览器故意这么做的

去除微信内浏览器（QQ浏览器按钮标签）点击出现蓝色框
input:focus{
		-webkit-tap-highlight-color:rgba(0,0,0,0);
    -webkit-user-modify:read-write-plaintext-only;
	}
-webkit-user-modify属性中的	read-write-plaintext-only 可以拆分read 和write
