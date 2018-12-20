# VSCode

### 1. VSCode Terminal的打开类型为powershell，如何修改

[https://blog.csdn.net/xiaojie802/article/details/82757932](https://blog.csdn.net/xiaojie802/article/details/82757932)

打开设置 File --> Preferences --> Settings 更改下面的配置

"terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe"

``` bash
powershell: "C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
cmd: "C:\\Windows\\System32\\cmd.exe",
bash: "D:\\*\\git\\bin\\bash.exe"
```