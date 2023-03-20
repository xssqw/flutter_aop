# flutter_aop


# 1.切换到flutter的git目录:/Users/alsc/flutter_aop/0001-aspectd.patch
# cd /Users/alsc/flutter_aop/0001-aspectd.patch
# 2.将aspectd源码中的git patch文件合并到flutter源码工程中，合并git patch:
# git apply --3way ~/Github/aspectd/0001-aspectd.patch     这句命令就是为了干扰flutter_tools里的common.dart文件
# 3.删除原有的的flutter编译工具：
# rm bin/cache/flutter_tools.stamp
# 4.重新构建新的flutter编译工具：
# flutter doctor -v

# 1、如果编译不成功，手动下载dart源码，git clone https://github.com/dart-lang/sdk.git，进行本地磁盘路径依赖
# 帮助文档： 1、https://www.jianshu.com/p/0200591f6afc    2、https://github.com/XianyuTech/aspectd
