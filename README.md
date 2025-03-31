# 使用统一镜像 
865383476351.ap-southeast-1.amazonaws.com/neoads-common/gcc-base:gcc7.4-bazelv5

# 本地无法获取统一镜像
使用docker_file文件夹进行本地构建

# 由于公司镜像仓库与本地不互通， 由于本地制作镜像
先在开发机上拉取镜像，使用docker save命令保存成文件， 通过https://bas.uneoads.me/ui/#/平台下载至本地

#目录说明
  fm_model: 实现fm模型(未完成)
  lr_model: 实现lr模型(未完成)
  runtime_info: 判定pod运行环境
  string: 字符串处理相关
  aws_s3: s3相关api
  s3_datamanager: s3业务封装

