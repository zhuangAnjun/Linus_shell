# Linus_shell
linux 常用命令

1. 使用`ps aux`可显示包含其他使用者的进程信息；

2. `grep str`可搜索包含该字符串的文件；

3. `top`命令可以查看 linux 系统详细运行情况，[命令详细](https://www.runoob.com/linux/linux-comm-top.html)；

4. `ar`命令可用来打包文件，`ar -x`在打包好的文件中抽取出子文件， `ar -r`插入或建立打包文，[命令详细](https://www.runoob.com/linux/linux-comm-ar.html);

5. `tail`用于显示文件尾部内容。`tail -f failname`显示文件尾部内容，并且不断刷新。`-n`指定尾部 n 行；

6. `kill -9`向进程发送强制终止信号；`kill -p pid`杀死指定进程；`killall`可用来杀死所有同名进程；

7. `od` 用于输出文件的八进制、十六进制或其它格式编码的字节.[命令详细](https://man.linuxde.net/od);

8. `tupdump` 用于抓取网络数据包,[参数详细](https://man.linuxde.net/tcpdump);

9. `nm` 命令显示关于指定 File 中符号的信息，文件可以是对象文件、可执行文件或对象文件库，[参数详细](https://linuxtools-rst.readthedocs.io/zh_CN/latest/tool/nm.html);

10. `c++filt`可以将编译后的符号逆向成原来的函数名；

11. `ldd` 打印程序的依赖库

12. `readelf`命令用来显示一个或者多个 elf 格式的目标文件的信息

13. `c++filt`可以将 name mangling 解析为原函数，经常在解决链接问题时使用

14. `crontab`命令用于linux系统定时执行命令，格式为`crontab [-u user] file crontab [-u user] [ -e | -l | -r ]`,其中file的格式为`time1 time2 time3 time4 time5 cmd`,[参数详情](https://linuxtools-rst.readthedocs.io/zh_CN/latest/tool/crontab.html)。**注意：直接执行`crontab new_file`会覆盖掉之前的记录**
