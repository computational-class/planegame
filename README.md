# planegame

## 下载游戏代码

https://github.com/computational-class/aircraftbattle

推荐使用Github Desktop下载到本机，例如我放在/github/planegame 文件夹当中。


## 使用pyinstaller打包成可执行软件

1. 首先，要确保安装好pyinstaller

2. 需将aircraftbattle.py中的路径名改为绝对路径：

        # 获取图片库和声音库路径
        # pyinstaller -F -w aircraftbattle.py
    
        img_dir = '/Users/datalab/github/planegame/pic/'
        
        sound_folder ='/Users/datalab/github/planegame/sounds/'

3. 在terminal中使用pyinstaller打包

> pyinstaller -F -w aircraftbattle.py
