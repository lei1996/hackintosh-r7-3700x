我的机型为

CPU: AMD r7 3700x
主板: 技嘉 x570 gaming x
GPU: XFX 5700 XT 8G黑狼
SSD: 西数 黑盘 250G

操作步骤，先在mac下下载好镜像，格式化之后，写入U盘， 具体参阅：https://support.apple.com/en-us/HT201372 
写入u盘之后，安装Clover BootLoader(Clover_v2.5k_r5103.pkg)这个文件.
自定义安装路径，选择U盘.
自定义选择安装，选择仅安装UEFI， 然后勾选安装到ESP分区.

之后解压 CCG.zip 文件，打开，挂载U盘的 EFI 分区， 将 本项目中的 EFI 里的BOOT、OC 文件夹复制进去.
删除U盘里的 CLOVER 文件夹

然后重启进入引导U盘， 开始安装