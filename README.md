CSSREM
-------------

#### 说明

本项目来源于 [flashlizi/cssrem](https://github.com/flashlizi/cssrem) ，由于原项目长时间没有更新和维护，issue中堆积很多问题没有解决，导致功能落后，很多功能没有得到支持，于是有了本项目。

本项目在插件原有功能上增加以下功能和优化：

1. 增加插件开关
2. 增加文件转换（一建转换整个文件）
3. 支持同时匹配多个光标
4. 增加属性的忽略（可自定义配置，如font-size，通常自适应网页字体不需要rem）


#### 如何帮助本项目变得更好

像朋友推广此插件，通过issue提意见，提需求，反馈BUG。谢谢！

----

一个CSS的px值转rem值的Sublime Text 3自动完成插件。

插件效果如下：

![效果演示图](cssrem.gif)


##### 安装

* 下载本项目，比如：git clone https://github.com/flashlizi/cssrem
* 进入packages目录：Sublime Text -> Preferences -> Browse Packages...
* 复制下载的cssrem目录到刚才的packges目录里。
* 重启Sublime Text。

##### 配置参数

参数配置文件：Sublime Text -> Preferences -> Package Settings -> cssrem

* `px_to_rem` - px转rem的单位比例，默认为40。
* `max_rem_fraction_length` - px转rem的小数部分的最大长度。默认为6。
* `available_file_types` - 启用此插件的文件类型。默认为：[".css", ".less", ".sass"]。