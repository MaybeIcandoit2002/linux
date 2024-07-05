# 必读：
<span style="color: red;"> vscode中使用快捷键ctrl+v，k（先后两次点击） </span>

| 指令和部分参数 | 备注
| :----- | :-----
|<span style="color: #3F9CD6;">reboot</span> | <span style="color: yellow;">\*</span> 重启
|||
|<span style="color: #3F9CD6;">halt</span> | <span style="color: yellow;">\*</span> 关机
|||
|<span style="color: #3F9CD6;">poweroff</span> | <span style="color: yellow;">\*</span> 关机
|||
|<span style="color: #3F9CD6;">shutdown</span> h:m/+m/now | <span style="color: yellow;">\*</span>关机或重启
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">重启
|  &emsp;&emsp;<span style="color: #3AC9A2;">-h | &emsp; <span style="color: grey;">关机
|  &emsp;&emsp;<span style="color: #3AC9A2;">-c | &emsp; <span style="color: grey;">取消
|||
|<span style="color: #3F9CD6;">who</span> | <span style="color: yellow;">\*</span> 当前用户
|||
|<span style="color: #3F9CD6;">date</span> | <span style="color: yellow;">\*</span> 当前时间
|||
|<span style="color: #3F9CD6;">cal</span> [<span style="color: lightblue;">month</span>] [<span style="color: lightblue;">year</span>] | <span style="color: yellow;">\*</span> 日历
|||
|<span style="color: #3F9CD6;">clear</span> | <span style="color: yellow;">\*</span> 清屏
|||
|<span style="color: #3F9CD6;">pwd</span> | <span style="color: yellow;">\*</span> 当前路径
|||
|<span style="color: #3F9CD6;">ls</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 查看目录
|  &emsp;&emsp;<span style="color: #3AC9A2;">-a | &emsp; <span style="color: grey;">显示所有
|  &emsp;&emsp;<span style="color: #3AC9A2;">-l | &emsp; <span style="color: grey;">详细
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">逆序
|  &emsp;&emsp;<span style="color: #3AC9A2;">-t | &emsp; <span style="color: grey;">时序
|  &emsp;&emsp;<span style="color: #3AC9A2;">-S | &emsp; <span style="color: grey;">长度排序
|||
|<span style="color: #3F9CD6;">cd</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 切换目录
|||
|<span style="color: #3F9CD6;">mkdir</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 创建目录
|  &emsp;&emsp;<span style="color: #3AC9A2;">-m | &emsp; <span style="color: grey;">权限
|  &emsp;&emsp;<span style="color: #3AC9A2;">-p | &emsp; <span style="color: grey;">逐级
|||
|<span style="color: #3F9CD6;">rmdir</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 删除目录
|  &emsp;&emsp;<span style="color: #3AC9A2;">-p | &emsp; <span style="color: grey;">逐级
|||
|<span style="color: #3F9CD6;">cat</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 查看文本文件
|  &emsp;&emsp;<span style="color: #3AC9A2;">-b | &emsp; <span style="color: grey;">非空行编号
|  &emsp;&emsp;<span style="color: #3AC9A2;">-n | &emsp; <span style="color: grey;">所有行编号
|  &emsp;&emsp;<span style="color: #3AC9A2;">-s | &emsp; <span style="color: grey;">空行合并
|||
|<span style="color: #3F9CD6;">more/less</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 从头、尾逐屏显示文本文件
|  &emsp;&emsp;<span style="color: #3AC9A2;">-[<span style="color: lightblue;">num</span>] | &emsp; <span style="color: grey;">一屏行数
|  &emsp;&emsp;<span style="color: #3AC9A2;">-c | &emsp; <span style="color: grey;">翻页前清屏
|  &emsp;&emsp;<span style="color: #3AC9A2;">+[<span style="color: lightblue;">mum</span>] | &emsp; <span style="color: grey;">开始行数
|  &emsp;&emsp;<span style="color: #3AC9A2;">-s | &emsp; <span style="color: grey;">空行合并
|||
|<span style="color: #3F9CD6;">head/tail</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 从头、尾读取文本文件
|  &emsp;&emsp;<span style="color: #3AC9A2;">-n | &emsp; <span style="color: grey;">行， 正数顺序，负数逆序
|  &emsp;&emsp;<span style="color: #3AC9A2;">-c | &emsp; <span style="color: grey;">字节，正数顺序，负数逆序
|  &emsp;&emsp;<span style="color: #3AC9A2;">-q | &emsp; <span style="color: grey;">不显示标题
|||
|<span style="color: #3F9CD6;">touch</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 修改文件时间标签，不存在则创建
|  &emsp;&emsp;<span style="color: #3AC9A2;">-a | &emsp; <span style="color: grey;">仅修改存取时间
|  &emsp;&emsp;<span style="color: #3AC9A2;">-c | &emsp; <span style="color: grey;">不创建
|  &emsp;&emsp;<span style="color: #3AC9A2;">-m | &emsp; <span style="color: grey;">仅修改修改时间
|  &emsp;&emsp;<span style="color: #3AC9A2;">-t | &emsp; <span style="color: grey;">指定时间：YYYYMMDDhhmm
|||
|<span style="color: #3F9CD6;">cp/mv/rm</span> [<span style="color: lightblue;">from</span>] [<span style="color: lightblue;">to</span>] | <span style="color: yellow;">\*</span> 复制、移动、删除文件或目录
|  &emsp;&emsp;<span style="color: #3AC9A2;">-f | &emsp; <span style="color: grey;">强制执行
|  &emsp;&emsp;<span style="color: #3AC9A2;">-i | &emsp; <span style="color: grey;">交互式
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">递归
|||
|<span style="color: #3F9CD6;">wc</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 统计文件信息
|  &emsp;&emsp;<span style="color: #3AC9A2;">-c | &emsp; <span style="color: grey;">字节数
|  &emsp;&emsp;<span style="color: #3AC9A2;">-l | &emsp; <span style="color: grey;">行数
|  &emsp;&emsp;<span style="color: #3AC9A2;">-w | &emsp; <span style="color: grey;">字数
|||
|<span style="color: #3F9CD6;">grep</span> [<span style="color: lightblue;">mode</span>] [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 查找匹配项 >正则表达
|  &emsp;&emsp;<span style="color: #3AC9A2;">-c | &emsp; <span style="color: grey;">行数
|  &emsp;&emsp;<span style="color: #3AC9A2;">-i | &emsp; <span style="color: grey;">不区分大小写
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">递归
|  &emsp;&emsp;<span style="color: #3AC9A2;">-n | &emsp; <span style="color: grey;">行号
|  &emsp;&emsp;<span style="color: #3AC9A2;">-v | &emsp; <span style="color: grey;">反选
|  &emsp;&emsp;<span style="color: #3AC9A2;">-w | &emsp; <span style="color: grey;">完全匹配
|||
|<span style="color: #3F9CD6;">ln</span> [<span style="color: lightblue;">from</span>] [<span style="color: lightblue;">to</span>] | <span style="color: yellow;">\*</span> 创建链接
|  &emsp;&emsp;<span style="color: #3AC9A2;">-s | &emsp; <span style="color: grey;">软链接
|  &emsp;&emsp;<span style="color: #3AC9A2;">-f | &emsp; <span style="color: grey;">强制执行
|||
|<span style="color: #3F9CD6;">chmod</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 修改权限
|  &emsp;&emsp;<span style="color: #3AC9A2;">ugoa | &emsp; <span style="color: grey;">当前、同组、其他、所有
|  &emsp;&emsp;<span style="color: #3AC9A2;">+-= | &emsp; <span style="color: grey;">增、减、设
|  &emsp;&emsp;<span style="color: #3AC9A2;">rwx | &emsp; <span style="color: grey;">读、写、执行
|  &emsp;&emsp;<span style="color: #3AC9A2;">XXX | &emsp; <span style="color: grey;">当前、同组、其他：八进制rwx
|||
|<span style="color: #3F9CD6;">chgrp</span> [<span style="color: lightblue;">group</span>] [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 修改所属组
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">递归
|||
|<span style="color: #3F9CD6;">chown</span> [<span style="color: lightblue;">user:group</span>] [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 修改所属用户
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">递 归
|||
|<span style="color: #3F9CD6;">umask | <span style="color: yellow;">\*</span> 设置新文件权限掩码，默认减除该项，参数如上
|||
|<span style="color: #3F9CD6;">groupadd</span> [<span style="color: lightblue;">name</span>] | <span style="color: yellow;">\*</span> 新增组
|  &emsp;&emsp;<span style="color: #3AC9A2;">-g | &emsp; <span style="color: grey;">组ID
|||
|<span style="color: #3F9CD6;">groupmod</span> [<span style="color: lightblue;">name</span>] | <span style="color: yellow;">\*</span> 修改组
|  &emsp;&emsp;<span style="color: #3AC9A2;">-g | &emsp; <span style="color: grey;">组ID
|  &emsp;&emsp;<span style="color: #3AC9A2;">-n | &emsp; <span style="color: grey;">组名：name
|||
|<span style="color: #3F9CD6;">groupdel</span> [<span style="color: lightblue;">name</span>] | <span style="color: yellow;">\*</span> 删除组
|||
|<span style="color: #3F9CD6;">useradd/usermod</span> [<span style="color: lightblue;">name</span>] | <span style="color: yellow;">\*</span> 新建、修改用户
|  &emsp;&emsp;<span style="color: #3AC9A2;">-d | &emsp; <span style="color: grey;">主目录位置
|  &emsp;&emsp;<span style="color: #3AC9A2;">-g | &emsp; <span style="color: grey;">所属组，默认100，支持组名或组ID
|  &emsp;&emsp;<span style="color: #3AC9A2;">-u | &emsp; <span style="color: grey;">用户ID
|||
|<span style="color: #3F9CD6;">userdel</span> [<span style="color: lightblue;">name</span>] | <span style="color: yellow;">\*</span> 删除用户
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">删除主目录
|<span style="color: #3F9CD6;">help/man</span> [<span style="color: lightblue;">order</span>] | <span style="color: yellow;">\*</span> 获取本地、联机帮助
|||
|<span style="color: #3F9CD6;">ps</span> | <span style="color: yellow;">\*</span> 查看进程状态
|  &emsp;&emsp;<span style="color: #3AC9A2;">a | &emsp; <span style="color: grey;">终端相关
|  &emsp;&emsp;<span style="color: #3AC9A2;">x | &emsp; <span style="color: grey;">非终端相关
|  &emsp;&emsp;<span style="color: #3AC9A2;">u | &emsp; <span style="color: grey;">面向用户格式
|||
|<span style="color: #3F9CD6;">kill</span> [<span style="color: lightblue;">ID</span>] | <span style="color: yellow;">\*</span> 结束进程
|  &emsp;&emsp;<span style="color: #3AC9A2;">-s | &emsp; <span style="color: grey;">信号
|||
|<span style="color: #3F9CD6;">sleep</span> [<span style="color: lightblue;">second</span>] | <span style="color: yellow;">\*</span> 等待
|||
|<span style="color: #3F9CD6;">gzip</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 解压缩
|  &emsp;&emsp;<span style="color: #3AC9A2;">-d | &emsp; <span style="color: grey;">解压
|  &emsp;&emsp;<span style="color: #3AC9A2;">-l | &emsp; <span style="color: grey;">详细信息
|  &emsp;&emsp;<span style="color: #3AC9A2;">-r | &emsp; <span style="color: grey;">递归
|  &emsp;&emsp;<span style="color: #3AC9A2;">-v | &emsp; <span style="color: grey;">压缩比
|||
|<span style="color: #3F9CD6;">df</span> | <span style="color: yellow;">\*</span> 查看磁盘
|  &emsp;&emsp;<span style="color: #3AC9A2;">-a | &emsp; <span style="color: grey;">所有
|  &emsp;&emsp;<span style="color: #3AC9A2;">-h | &emsp; <span style="color: grey;">整理
|||
|<span style="color: #3F9CD6;">du</span> [<span style="color: lightblue;">adress</span>] | <span style="color: yellow;">\*</span> 目录或文件的磁盘占用
|  &emsp;&emsp;<span style="color: #3AC9A2;">-a | &emsp; <span style="color: grey;">所有
|  &emsp;&emsp;<span style="color: #3AC9A2;">-b | &emsp; <span style="color: grey;">单位：bytes
|  &emsp;&emsp;<span style="color: #3AC9A2;">-c | &emsp; <span style="color: grey;">总计
|  &emsp;&emsp;<span style="color: #3AC9A2;">-h | &emsp; <span style="color: grey;">整理
|||
|<span style="color: #3F9CD6;">fdisk</span> [<span style="color: lightblue;">disk</span>] | <span style="color: yellow;">\*</span> 查看磁盘分区
|  &emsp;&emsp;<span style="color: #3AC9A2;">-l | &emsp; <span style="color: grey;">详细

----- ----- ----- ----- ----- ----- ----- ----- ----- -----
|||
| :----- | :-----
|通配符：
|? | <span style="color: yellow;">\*</span> 任意单字占位
|* | <span style="color: yellow;">\*</span> 任意多字占位
|[<span style="color: lightblue;">ab-ef</span>] | <span style="color: yellow;">\*</span> 单字占位：acdef

|||
| :----- | :-----
|正则表达：
|^ | <span style="color: yellow;">\*</span> 开头
|$ | <span style="color: yellow;">\*</span> 结尾
|. | <span style="color: yellow;">\*</span> 单字占位
|* | <span style="color: yellow;">\*</span> 重复前一位任意次
|+ | <span style="color: yellow;">\*</span> 重复前一位至少一次
|? | <span style="color: yellow;">\*</span> 重复前一位一次或零次
|[] | <span style="color: yellow;">\*</span> 单字占位
|{m,n} | <span style="color: yellow;">\*</span> 重复前一位m-n次
