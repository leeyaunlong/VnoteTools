# VnoteTools
Import markdown file to Vnote note directory


 一直用有道云来做笔记,结果看md的时候老是出现各种小毛病,虽然解决方法很简单(重启,打开新窗口之类的),但是还是让我很不爽.<br>
 几次之后决定换个云笔记.在下载了印象/为知/OneNote并试用之后,发现仍然不能满足我的需求<br>
 印象笔记UI看着十分难受,并且交互也不如有道云,虽然功能很强大,但是被我pass了.<br>
 为知笔记的md支持应该是最好的了,但是预览时渲染进度肉眼可见,让我十分难受.<br>
 OneNote虽然也很强大,但是本身不支持md,需要用第三方插件来完成.<br>
 一番尝试后,最终决定使用Vnote+坚果云来进行笔记加云同步.<br>
 
 不得不说Vnote还是很符合我心意的,然而虽然他能打开并查看外部md文件,但是好像并不能将外部的文件以及文件夹在左侧目录显示并管理,这是很让人难受的.<br>
 于是写了一个小程序来将复制到工作空间内的外部md文件添加到Vnote的配置文件中,让这些外部文件也能显示在目录里.<br>
 
 
 
 ### 使用方法
 1. 用Vnote新建一个笔记本
 2. 将外部md文件以及文件夹复制到笔记本目录中
 3. 将程序复制到笔记本根目录并运行
 4. 程序会将从根目录开始的每一个markdown文件以及文件夹添加到Vnote的配置文件中
 5. 好像在笔记本的根目录不能查看md文件,所以笔记本根目录最好都是文件夹,在文件夹中来管理md文件
 6. 执行完毕后,在Vnote笔记本根目录的空白处右击->选择从磁盘重新加载即可

### JDK版本需要1.8及以上
