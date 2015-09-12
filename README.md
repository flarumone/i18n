##Flarum 简体中文 / Simplified Chinese 语言包  
基于 [Flarum](http://flarum.org) 原生语言包翻译  
整体语言风格较细腻自然  
符合多数中国人思维习惯  
* **DEMO:** [Flarum 中国第一站](http://f.szlt.net/)  
  
###关于本补丁
* 前台支持多语言切换  
* 支持中文搜索  
* 替换默认的google字体cdn为360提供  
* 后台管理界面也已实现中文简体化  
* 简体中文语言包的命名为 `zh_CN.yml`  
  
###安装说明  
1.下载后解压 覆盖至Flarum根目录  
2.修改默认的本地语言为简体中文`zh_CN` 请执行这条SQL语句  
``UPDATE `flarum`.`config` SET `value` = 0x636e WHERE `config`.`key` = 'default_locale';``  
3.删除/flarum/assets/目录下 除avatars和fonts文件夹以外的所有文件  
4.刷新页面即可 Ctrl+F5 更配哦  
  
**GitHub:** <https://github.com/mokecc/Flarum-zh_CN/>  
  
[打包ZIP下载>>](https://github.com/mokecc/Flarum-zh_CN/archive/master.zip)  
    
###更新记录  
####2015/8/30 
1.让插件的多语言变得更聪明  
通过继承核心的默认语言设定 去识别您是否添加了对应的语言包  
我将会把这个思想提交给核心开发组  
2.增加后台翻译文件 已实现前后台的中文简体化  
  
###获取帮助  
如有疑问或建议  
请直接提出问题  
  
[Issuse on GitHub>>](https://github.com/mokecc/Flarum-zh_CN/issues)  
  
###特别鸣谢(排名部分先后，向她们致敬)
####小黄鸡 **Jsthon Wong** 同学  
此语言包原始翻译由他完成 [https://github.com/jsthon/Flarum-zh-CN](https://github.com/jsthon/Flarum-zh-CN)  
关于该版翻译不恰当的请找他 下面是他的联系方式  
* **博客/Blog:** <http://jsthon.com>  
* **邮箱/Mail:** jsthonwong@gmail.com  

####[不许笑 **binaryoung** 同学](https://github.com/binaryoung)  
他解决了中文搜索的问题  

####[**Fly** 同学](http://binaryoung.com/)
他完成了后台的翻译工作  
