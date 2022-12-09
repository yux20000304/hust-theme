# hust-theme

> 这是一款添加了华科元素的ppt模板，通过在vscode中使用了marp插件进行实现

## 文件目录及用途
```
hust-theme
├─.vscode
├─images
├─svg
└─themes
```
- vscode文件夹中设置了工程文件配置
- images保存了需要使用的图片资源
- svg保存了矢量图
- themes文件夹中包含了css模板
    - structure.css文件设置了基本格式
    - schema.css文件设置了字体大小颜色等参数
    - hust.css文件导入了上述两个模板并添加了hust元素的图片

## 使用指南

可以直接复制md文件中对应页，也可以修改schema进行参数修改，不建议直接修改structure.css文件，直接在hust.css文件中对原有设置进行修改，会自动覆盖原有设置。

