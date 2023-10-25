# Typora + PicGO +GitHub+pandoc+Watt Toolkit实现Markdown笔记

残夜的九月



## 网址链接

Typora中文站 https://typoraio.cn/

Typora官网 https://typora.io/（国内访问困难）

PicGO官网 https://molunerfinn.com/PicGo/

GitHub下载PicGOhttps://github.com/Molunerfinn/picgo/releases

pandoc官网 https://pandoc.org/installing.html

Watt Toolkit官网 https://steampp.net/download

GitHub官网 https://github.com/



## 下载必备软件

根据链接下载应用

![image-20231008163528715](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008163528715.png)

![image-20231008164143429](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008164143429.png)

![image-20231008164326246](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008164326246.png)

![image-20231008173929863](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008173929863.png)

![image-20231008164516674](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008164516674.png)

上面的软件都下载好后，解压下压缩包。

![image-20231008164858659](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008164858659.png)

解压后我们先将typora和PicGO安装好，安装过程就不说了。



## 配置pandoc

pandoc可以帮助我们导出word等其他类型的格式文件

右键点击Typora图标

![image-20231007201402484](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231007201402484.png)

点击 “打开文件所在的位置”

![image-20231008165558430](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008165558430.png)

将位置复制下来（防止操作时找不到位置）

![image-20231008165829545](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008165829545.png)

然后我们打开刚解压好的pandoc的文件夹，然后点开找到“pandoc.exe”这个文件复制粘贴或拖拽到typora文件夹下

![image-20231008172126182](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008172126182.png)

复制好后就是下面的样子

![image-20231008172233959](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008172233959.png)



以上操作完成后点击 “文件”  >> "偏好设置" 

![image-20231007202032763](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231007202032763.png)

![image-20231007201750576](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231007202107582.png)

找到"PicGO路径"将picgo的路径粘贴上

![image-20231008172449014](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008172449014.png)

![image-20231008172810483](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008172810483.png)

或直接选上就可以了

![image-20231008173314070](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008173314070.png)

## 配置Watt Toolkit

这里的加速器是重点（大多数报错都是以为没有开这个加速器）

双击并打开Watt Toolkit

![image-20231008191823943](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008191823943.png)

勾选GitHub后点击一键加速

![image-20231008191740701](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008191740701.png)

为了不必要的麻烦我们将设置里的开机自启动和加速打开。

点击设置

![image-20231008192123988](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008192123988.png)

打开后找到通用设置，将“开机自启动”打开

![image-20231008192219814](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008192219814.png)

然后打开“网络加速”

![image-20231008192450070](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008192450070.png)

打开后点击“代理设置”

![image-20231008192528866](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008192528866.png)

将 “启动时自动启动加速”

![image-20231008192600889](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008192600889.png)



## 配置GitHub

这里就不讲如何注册和登录GitHub了

登录GitHub

![image-20231008193623339](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008193623339.png)

![image-20231008193706226](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008193706226.png)

登录后点击创建新的库

![image-20231008193809310](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008193809310.png)

或这里也可以创建

![image-20231008194022386](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008194022386.png)

填写名称

![image-20231008194305908](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20231008194305908.png)

将“Public”、“Add a README file”给选上 然后点击绿色按钮创建

![image-20231008194600656](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008194600656.png)

![image-20231008194907740](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008194907740.png)

然后点击右上角头像、点击“Settings”

![image-20231008195023327](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195023327.png)

划到底部带点击“Developer Settings”

![image-20231008195122551](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195122551.png)

点击 “tokens”

![image-20231008195323435](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195323435.png)

创建新的钥匙

![image-20231008195435208](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195435208.png)

输入登录密码

![image-20231008195529375](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195529375.png)

输入名称![image-20231008195644028](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195644028.png)

选择永久

![image-20231008195746518](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195746518.png)

勾选 “repo”

![image-20231008195841075](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195841075.png)

滑倒底点击绿色图标

![image-20231008195941641](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008195941641.png)

复制下来等下要用（刷新页面后就看不到了，建议保存下）

![image-20231008200238894](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008200238894.png)



## 配置PicGO

这里我们打开PicGO

![image-20231008200445930](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008200445930.png)

![image-20231008200530121](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008200530121.png)

打开后我们先点击“PicGO设置”将“开机自启”打开

![image-20231008200649607](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008200649607.png)

然后打开“图床设置”再找到GitHub

![image-20231008200838635](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008200838635.png)

这里注意自定义域名要要用加速域名（因为github服务器在国外）https://cdn.jsdelivr.net/gh/用户名/库名

将下面域名复制下根据格式填就行

https://cdn.jsdelivr.net/gh/

填完后点击确定

![image-20231008201136387](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008201136387.png)

然后点击设为默认图床就行

![image-20231008201638172](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008201638172.png)



## 配置Typora

打开Typora点击“文件”“偏好设置”

![image-20231008202026114](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008202026114.png)

点击“图像”

![image-20231008202153043](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008202153043.png)

插入图片时选为“上传图片”

![image-20231008202314707](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008202314707.png)

将上传服务设定选为“PicGO(app)”

![image-20231008202418294](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008202418294.png)

这里右键点击“打开文件所在位置”

![image-20231008202621946](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008202621946.png)

将路径复制粘贴下来

![image-20231008202834095](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008202834095.png)

然后将路径输入到“PicGO路径”内 

![image-20231008202924017](https://cdn.jsdelivr.net/gh/cxiaofei/images/image-20231008202924017.png)

到这里就结束了

