只需要选择⼀个⽬录作为⼯作空间， 然后将GOPATH环境
变量设置为该路径。
必要时， Go语⾔⼯具会创建⽬录。 例如：
$ export GOPATH=$HOME/gobook # 选择⼯作⽬录
$ go get gopl.io/ch1/helloworld # 获取/编译/安装
$ $GOPATH/bin/helloworld # 运⾏程序
Hello, 世界 # 这是中⽂
运⾏这些例⼦需要安装Go1.5以上的版本。
$ go version
go version go1.5 linux/amd64
如果使⽤其他的操作系统, 请参考 https://golang.org/doc/install 提供的说明安装。
