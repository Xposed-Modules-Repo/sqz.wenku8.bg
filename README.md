## 原代码仓库

[OverrideWenku8ReadingBackground](https://github.com/Z-Siqi/OverrideWenku8ReadingBackground)

## 应用简介

强制将 [轻小说文库(org.mewx.wenku8)](https://github.com/MewX/light-novel-library_Wenku8_Android) 默认阅读背景修改为纯白色背景

### 制作原因
*单纯因为没有找到使用自定义图片的方法而写了这个 xposed 模块*

当然现在已经知道改的方法了 🤡，但这也提示着设计的重要性，即切换的功能应该使用符合直觉的按钮。

~为了不让这个项目失去存在的意义~，因此也添加了一些其它的优化，具体参见下面的详细描述。

### 详细描述
这个 Xposed 模块即在把我不喜欢的默认黄色纸张阅读背景替换为纯白色背景以方便我阅读轻小说。除此之外再顺便再让阅读模式(日间/夜间)自动随着系统的省电模式/黑暗主题状态更改

> 在轻小说文库`1.25`版本中的特别功能：阻止部分设备疑似因验证原因跳转到一个只能选择退出还又没描述的页面。
