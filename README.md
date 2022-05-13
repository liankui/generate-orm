# generate-orm

1、安装完 Go（要求 1.14 以上版本）后，可以使用以下 Go 命令安装 Gen。
`go get -u gorm.io/gen`

2、在工程中导入引用 Gen:
import "gorm.io/gen"

3、在根目录执行generate.sh文件：
`./generate.sh`

4、执行成功即生成dao文件夹，包含model和query目录
