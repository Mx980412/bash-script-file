# bash脚本文件

1. 创建一个文件（后缀名无所谓）
2. 添加执行权限（Windows不用，mac用）
   * `chmod +x 文件名`
3. 文件里：
   1. 加shebang：指定程序运行脚本
      * shebang：`#!/usr/bin/env 脚本解释器名称`
        1. 脚本解释器：如sh（bash），js...
   2. 写执行的命令
      * `$1`：可创建任何文件名
4. 运行即可执行
   * `./文件名的路径 xxx`或`sh 文件名的路径 xxx`
   1. 没加Path，就要写全正确的路径
   2. 加了Path，只用文件名就能执行
   3. 加了shebang，删掉sh用文件名也能执行（但要用正确的路径）
   
## 一键搞定的bash脚本文件

* 运行： `./一键搞定 xxx`或`sh 一键搞定 xxx`，就会创建xxx目录
