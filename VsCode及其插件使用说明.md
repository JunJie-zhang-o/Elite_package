

## Vscode及其插件使用

- ### Vscode下载安装

  ###### 点击[官网下载](https://code.visualstudio.com/)安装

  ------

  #### 插件包安装

  > Extension Packages
  >
  > 只需本地安装本插件即可安装下文所有插件
  >
  > 链接：https://cloud.elite-robot.org/s/yoELPw8DBez6XLs

  ###### 安装

  ![](https://ae01.alicdn.com/kf/Ub681a32fbd434aa5b133617acc5bd413t.jpg)

- ### 插件的下载

  ![](https://ae01.alicdn.com/kf/Ud0e5bfe4bedd43b7ad8477e22847ff90O.jpg)

- ### 插件介绍和使用

  1. ##### 中文汉化包-Chinese (Simplified) Language Pack for Visual Studio Code

  2. ##### EliteScript_lua

     ###### 安装

     ![](https://ae01.alicdn.com/kf/U96f5cb6265ab455dad5a2895f3b2ba7f3.jpg)

     ###### 使用

     ![](https://ae01.alicdn.com/kf/U7fecf5c6c84948158aa796689cc0a96bO.jpg)

     ###### 切换语言模式

     ![](https://ae01.alicdn.com/kf/Uc91805a8862342fd9b16545b260c41f1H.jpg)

     > 在vscode中切换为lua语言模式后，运行lua程序，需要lua环境和Code Runner插件支持

  3. ##### EliteScript_JBI

     ###### 安装

     ![](https://ae01.alicdn.com/kf/Ud0ba9307af024f138ed27d4b752c1293u.jpg)

     ###### 使用

  4. ##### Sftp文件传输插件-SFTP

     > 使用SFTP需将电脑和远端设备置于同一局域网内！！！

     ###### 安装SFTP插件

     ![](https://ae01.alicdn.com/kf/Uf91daf8d82c4442394c37c8efb4ec5ba0.jpg)

     ###### 配置SFTP参数

     > 配置SFTP参数，必须建立一个文件夹，在该文件夹下配置的参数只对该文件夹生效
     >
     > 打开vscode命令面板**(CTRL+SHIFT+P)**，输入**SFTP：config** 配置参数
     >
     > 输入**SFTP：List**打开远端设备对应配置路径的列表

     ![](60386794ada63.jpg)

     > 对应的jbi文件放置在WorkSpace文件下
   >
     > 对应的lua脚本文件放置在luadir文件下
  
     ###### SFTP配置内容-链接jbi文件地址 
  
     ```json
     {
         "name": "My Server",
         "host": "192.168.1.200",
         "protocol": "sftp",
         "port": 22,
         "username": "root",
         "password": "elite2014",
         "remotePath": "/rbctrl/",
       "uploadOnSave": true
     }
   
     ```
  
     ###### SFTP配置内容-链接lua文件地址 
  
     ```json
     {
         "name": "My Server",
         "host": "192.168.1.200",
         "protocol": "sftp",
         "port": 22,
         "username": "root",
         "password": "elite2014",
         "remotePath": "/rbctrl/",
       "uploadOnSave": true
     }
   
     ```

     ###### 从远端设备上传至电脑

     > 下载或者上传文件需保证当前文件夹下有创建的SFTP配置文件夹

     使用命令方法

     ![](https://ae01.alicdn.com/kf/U793071f26e6241c88056aef2049e9c95o.jpg)

     使用SFTP的侧边栏

     ![](https://ae01.alicdn.com/kf/Ud984c25bbedf4ec3ab390e0b4105f8dd9.jpg)

     ###### 从电脑下载到远端设备

     > 修改后保存即可自动下载，保存后左下角显示字样 **done filename.type** 即成功

     ![](https://ae01.alicdn.com/kf/U576d24ce4e504c798b6004ae59cd5f8er.jpg)

  5. ##### 彩虹括号-Bracket Pair Colorizer 2

     ###### 安装与显示效果

     ![](https://ae01.alicdn.com/kf/U72f0443c710948ff98a18eb350f843f98.jpg)

     

  6. ##### 彩虹缩进-indent-rainbow

     ###### 安装与显示效果

     ![](https://ae01.alicdn.com/kf/U5e5dd13c1b804505bcef75696ed2b645v.jpg)

  7. ##### 翻译-Comment Translate

     ###### 安装与使用

     ![](https://ae01.alicdn.com/kf/Uc214e4e8522940dfbf276013567126adR.jpg)

     ![](https://ae01.alicdn.com/kf/U6ddd62dce9d5470bbdfaebf903276588P.jpg)

  8. ##### filesize

     ###### 安装与使用

     ![](https://ae01.alicdn.com/kf/U46bff27e8e744d0ab353779a11057436f.jpg)
  
  9. ##### Code Runner
  
     ###### 安装
  
     ![](https://ae01.alicdn.com/kf/U519bcbf58efa48c395425d8dbcc6ffefo.jpg)
     
     ###### 设置
     
     
     
     > ###### Code Runner运行程序需有相对应的编程环境支持
     
     ------
     
     #### 例：安装Lua环境，用VsCode运行lua程序
     
     ##### 		lua环境安装包：https://cloud.elite-robot.org/s/9agiFSb2xy8tdR3
     
     ##### 		配置用户变量和系统变量：
     
     ![](https://ae01.alicdn.com/kf/U4d108d37c026400f8ade4f1052b44f49s.jpg)
     
     ##### 		检查用户变量
     
     ![](https://ae01.alicdn.com/kf/U4d6bbc841a7b4999b8bf5d204cf83b1aS.jpg)
     
     ##### 		Vscode运行lua程序
     
     ![](https://ae01.alicdn.com/kf/U6817f72f2ed141558a9d64e09ba6184aT.jpg)
     
     
  
  