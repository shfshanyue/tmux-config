## Introduce

[tmux：打造精致与实用并存的终端](https://segmentfault.com/a/1190000008188987)

## Config
``` sh
$ git clone git@github.com:shfshanyue/tmux-config.git
$ cp tmux-config/.tmux.conf ~/.tmux.conf
```

## Screencast

![Screencast One](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/tmux1.jpeg)
![Screencast One](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/tmux2.jpeg)

## Animation

### Attach
```
$ tmux new -s shanyue   # 新建session
<prefix> + d            # detach client
$ tmux a -t shanyue     # attach
```

![Attach](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/attach-origin.gif)

### Split
```
<prefix> + %  # 水平分屏
<prefix> + "  # 垂直分屏
```

![Split Window](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/split-origin.gif)

### Multi Window
```
<prefix> + c  # 新建窗口
```

![Multi Window](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/multi-window.gif)

### Find Window
```
<prefix> + f  # 根据关键字查找
<prefix> + 4  # 切换到第四个窗口
<prefix> + a  # 切换到最近的窗口
```

![Find Window](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/find-window.gif)

### Next Layout
```
<prefix> + space
```

![Next Layout](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/respace.gif)

### Maximise
```
<prefix> + z
```

![Maximise](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/prefixz-origin.gif)

### Copy Mode
```
<prefix> + [
[Vim Goto Command]  # 任意 vim 跳转命令
```

![Copy](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/copy-origin.gif)

### Mouse Mode
```
$ tmux set mouse on # 通过鼠标滚动屏幕，切换窗口
```

![Mouse Mode](https://raw.githubusercontent.com/shfshanyue/tmux-config/assets/mouse-origin.gif)
