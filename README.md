# fastlanebuild
####本脚本是基于gym的iOS工程打包脚本,打包效率是普通Xcode的两倍以上,但是只适用于CocoaPods的工程项目,可以选择自动上传到fir.
####使用前须知:
####按照下面的提示依次替换ruby镜像,安装gym,安装fir,都只需安装一次
####======================================================
####       1.替换ruby镜像为淘宝
####   $ gem sources --remove https://rubygems.org/
####   $ gem sources -a https://ruby.taobao.org/
####   $ gem sources -l
####   *** CURRENT SOURCES ***
####   https://ruby.taobao.org // 确定只有这一个
####=====================================================
####       2.安装gym
####   $ sudo gem install gym
####=====================================================
####       3.安装fir
####   $ sudo gem install fir-cli
####=====================================================
##注意:只能打包CocoaPods工程,先要设置脚本权限: chmod +x 本脚本.sh
##用法:将脚本拖入到终端,配置好firtoken
##只需要:脚本+工程绝对路径
##打包好的文件放在了当前工程下buildPackages文件夹中
##提醒:control+C 退出正在执行的脚本
