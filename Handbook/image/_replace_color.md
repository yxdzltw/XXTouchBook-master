### 颜色替换 \(**:replace\_color**\)


#### 声明
```lua
图像 = 图像:replace_color(原色, 替换色[, 原色相似度])
```


#### 参数及返回值
- 图像
    - 图片对象，当前操作的图片对象
- 原色
    - 整数型，原来的颜色
- 替换色
    - 整数型，需要变成的颜色
- 原色相似度
    - 整数型，可选参数，颜色相似度，范围 0~100，默认 100


#### 说明
> 将图片对象上某种颜色 (或及近似色) 替换为另外的颜色  
> 会对对象本身产生影响  
> 性能上，该函数操作过程不产生数据拷贝  


#### 示例  
[`二维码背景色替换`](/Handbook/utils/utils.qr_encode.md)  
