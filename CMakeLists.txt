#最低版本要求
cmake_minimum_required(VERSION 2.8)

#项目名称
project(Pacman)

#查找当前目录下所有源文件
#并保存当前目录到变量DIR_SRCS中
aux_source_directory(. DIR_SRCS)

#指定生成目标
add_executable(Pacman ${DIR_SRCS})