### 产生一个随机数 \(**sys\.rnd**\)


#### 声明
```lua
随机数字 = sys.rnd()
```


#### 参数及返回值
- 随机数字
    - 整数型，返回一个随机数字，范围 0~4294967295


#### 说明
> 产生一个真随机数


#### 示例  
```lua
math.randomseed(sys.rnd()) -- 初始化随机因子为一个真随机数
local r = math.random(1, 100) -- 产生一个 1~100 范围的随机数
```
