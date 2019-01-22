### 配置对话框的位置及尺寸 \(**:set\_frame**\)


#### 声明
```lua
对话框对象 = 对话框对象:set_frame(横坐标, 纵坐标, 宽度, 高度)
```


#### 参数及返回值
- 横坐标, 纵坐标
    - 整数型，对话框对象左上角位置的横坐标及纵坐标
- 宽度, 高度
    - 整数型，对话框对象宽高，如果不设置默认是全屏宽高
- 对话框对象
    - 对话框，返回对话框本身


#### 说明
> **这个方法在 1\.2\-1 版以上方可使用**  
> 配置对话框的位置及尺寸，使用方角  


#### 示例  
```lua
local dlg = dialog()
dlg:set_frame(0, 0, 600, 800)
dlg:show()
```
