# 智能药盒
背景介绍：
    智能药盒用来存放老年人需要吃的药，要摇动手柄达到一定的电量，智能药盒才会弹开。每个老年人都有一个自己的药盒，每个人的发电量会保存到数据库当中。数据库里有每个用户的名字，头像，发电量，排名等数据。
    要根据用户的发电量，进行名次排序。
    有的用户的发电量如果低于标准发电量的值，数值要用红色标出。
 
## 电脑环境配置：
### 1.下载xampp建站集成软件包（（Apache+MySQL+PHP+PERL））
 链接：https://www.apachefriends.org/zh_cn/index.html
### 2.编程编辑器：sublime text 3
链接：https://www.sublimetext.com/3
1.syntax settings语法设置
2.package control
(1)tools————>install package control————>command palette————>install package（选中，并用鼠标单击）
3.ctrl+F快捷键
4.layout 多窗格

3.Aphche以及mysql要调成start模式。
4.文件要保存在 C:\xampp\htdocs的根目录下
 暂定文件夹的名字为：yaohe
 
 需要准备的文件：
 1.文件名：模拟数据。
 文件格式：CSV UTF-8（逗号分隔）
 （模拟数据最初以excel文件建立，完成后，保存为CSV UTF-8的格式）
 注：模拟数据中的用户头像一栏，填写的内容图像的命名。xxx.png或xxx.jpg
 2.用户的头像
 图像格式：png/jpg
 图像命名规则：英文或拼音
 图像的大小：44px乘44px
 使用软件：photoshop
 2.把模拟数据导入到mysql中
 打开浏览器，在浏览器的地址栏输入：http://localhost/phpmyadmin/   即可进入数据库后台。
 在界面的左侧选择某一数据库。
 在界面右侧的导航栏上，选择结构，可以修改，列名。列最好用英文或拼音来命名。
 
