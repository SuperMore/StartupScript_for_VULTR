# StartupScript_for_VULTR
[arai2py](https://github.com/SuperMore/Aria2Py) 的vultr脚本,不过搬瓦工或者lindo等所有服务器都能用。

[Vultr](https://www.vultr.com/?ref=8126287)初始化启动脚本，用于在新建vultr等服务器的时候，直接安装[arai2py](https://github.com/SuperMore/Aria2Py)，以及jupyter lab（用于免ssh登录）。

# 配置
## 复制文件
自行复制[Firstboot_script](https://github.com/SuperMore/StartupScript_for_VULTR/blob/main/Firstboot_script)中的内容到vultr -> product -> Startup Scripts 

## rclone配置
在复制的一串代码中找到以下内容,并将rclone配置文件全部粘贴于此。

```
#请将 rclone配置文件粘贴于下框， rclone配置文件一般是/root/.config/rclone/rclone.conf
##############################################################################################
#————————————————————————————————————————————————————————————————————————————————————————————#



#————————————————————————————————————————————————————————————————————————————————————————————#
##############################################################################################
```

## jupyter密码配置：
在配置文件末尾，同上一项一样修改即可。默认密码114514，可以不改。或者后续通过输入以下命令修改：
```
# 修改jupyter 密码
 jupyter lab password
```
# VPS推荐
[vultr推广优惠](https://www.vultr.com/?ref=8126287)

[搬瓦工](https://bwh81.net/aff.php?aff=63547) 

[搬瓦工](https://bandwagonhost.com/aff.php?aff=63547)
