# docker && docker compose 离线安装
## file 文件
### daemon.json 镜像仓库
### docker 命令补全提示
### docker-28.1.1.tgz 离线docker安装包
### docker-compose 命令文件
## script 脚本
### 0_create_path.sh 创建目录
### 1_copy_file_to_path.sh 文件复制
### 2_install_docker.sh 离线安装docker
### install.sh 安装docker所需脚本
## .install-docker.sh 安装docker脚本
## 安装
### chmod 755 ./install-docker.sh
### chmod 755 ./file/docker-compose
### chmod -R 755 ./script/
### 执行 ./install-docker.sh

## 参考
### docker离线安装包
https://download.docker.com/linux/static/stable/x86_64/
### docker安装脚本
https://github.com/Jrohy/docker-install/
### docker compose 文件
https://github.com/docker/compose/releases
