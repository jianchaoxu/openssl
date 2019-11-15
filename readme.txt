openssl源码编译步骤及需要注意的几点问题：

1、在终端下运行本目录下OpenSSL-ios-master文件夹下的build-libssl.sh文件即可，该脚本将自动解压对应目录下的源码openssl压缩包（编译前需准备好，放于脚本同目录下）.
2、成功编译后将生成三个文件夹，分别为bin、include、lib，其中lib支持armv7及arm64架构，默认同时生成opssl-tvos的库，项目中未用到，项目中用lib下面的libssl.a及libcryto.a两个lib及对应的include.
