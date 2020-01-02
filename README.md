## less
>使用vscode的Easy Less插件编译less文件
  init.less 初始化样式文件
  mixin.less mixin文件
  var.less  变量文件包括颜色变量等
### 变量命名规则
颜色变量颜色加上对应的rgb值例如:
```less
// #e10030
@rede1: #e10030;
```
mixin css 属性名小驼峰例如:
```less
// box-shadow
.boxShadow {
   box-shadow: 0 0 0 1px #000;
}
.transform {
  transform: translate(0, 50px);
}
```
