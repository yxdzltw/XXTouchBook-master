### 前言

代码片段模板 `.snippet` 是一个特殊的 Lua 文件, 描述了如何使用一个或多个「代码片段选择器」产生的结果生成纯文本代码片段或其它对象。生成的对象，可以保存到 XUI 配置当中，如果是文本对象，亦可以快速插入代码编辑器。

「代码片段选择器」，指的是一系列用于生成「代码片段」的预置选择器组件，选择器类型包括：

- 单个应用程序选择器 `app`
- 多个应用程序选择器 `apps`
- 地理位置选择器 `loc`
- 虚拟按键选择器 `key`
- 单个图像位置选择器 `pos`
- 单个图像颜色选择器 `color`
- 单个图像位置与颜色选择器 `poscolor`
- 多个图像位置与颜色选择器 `poscolors`
- 图像区域选择器 `rect`

