1. adb shell setprop log.tag.binderhook DEBUG 打开Hook开关
2. adb shell setprop log.tag.<ProcessName>.binderhook DEBUG 针对某个进程打开log开关(第1步是前提)
3. 如果想要打印接口的栈信息，将方法名按行隔开，放入/sdcard/hook/hooked_method.txt中
注意：三方应用需要被赋予文件访问权限。