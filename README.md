REMCSS
-------------

一个CSS的rem值转px值的Sublime Text 3自动完成插件。

插件效果如下：

![效果演示图](remcss.gif)

##### 安装

* 下载本项目，比如：git clone https://github.com/retechs/rem2px
* 进入packages目录：Sublime Text -> Preferences -> Browse Packages...
* 复制下载的remcss目录到刚才的packges目录里。
* 重启Sublime Text。

##### 配置参数

参数配置文件：Sublime Text -> Preferences -> Package Settings -> cssrem

* `rem_to_px` - px转rem的单位比例，默认为100。
* `max_px_fraction_length` - px转rem的小数部分的最大长度。默认为6。
* `available_file_types` - 启用此插件的文件类型。默认为：[".css", ".less", ".sass"]。
