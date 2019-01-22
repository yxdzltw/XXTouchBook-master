### 设置图片对象某点颜色 \(**:set\_color**\)


#### 声明
```lua
图像 = 图像:set_color(横坐标, 纵坐标, 颜色)
```


#### 参数及返回值
- 图像
    - 图片对象，当前操作的图片对象
- 横坐标, 纵坐标
    - 整数型，需要设置颜色的点于当前图片对象上的坐标
- 颜色
    - 整数型，需要设置的颜色值


#### 说明
> 设置图片对象某点颜色  
> 会对对象本身产生影响  
> 性能上，该函数操作过程不产生数据拷贝  
