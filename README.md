# Shell

用到了 @Vicer 萌咖大佬的脚本，感谢~（快去修OneDrive直链API啊！！

支持重装的系统：
Debian 9/10
Ubuntu 18.04/16.04
CentOS 6/7
自定义DD镜像

特性/优化：
自动获取IP地址、网关、子网掩码
自动判断网络环境，选择国内/外镜像，再也不用担心卡半天了
超级懒人一键化，无需复杂的命令
解决萌咖脚本中一些导致安装错误的问题
CentOS 7 镜像抛弃LVM，回归ext4，减少不稳定因素

使用方法：非常简单
wget --no-check-certificate -O AutoReinstall.sh https://git.io/AutoReinstall.sh && bash AutoReinstall.sh
复制代码


补充：我又看了一下，发现一些玄学问题得不到解释：在阿里云上测试全功能可用，在aws上测试dd功能正常，其他不太行。。。
