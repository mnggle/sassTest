# sassTest
my sassTest demos

# demo01
1. 单文件编译
```
sass <要编译的Sass文件路径>/style.scss:<要输出CSS文件路径>/style.css
```
2. 多文件编译
```
sass sass/:css/
```
3. 检测代码变化，自动编译
```
sass --watch <要编译的Sass文件路径>/style.scss:<要输出CSS文件路径>/style.css
```
# demo02 嵌套
1. style.css 选择器嵌套
2. main.css 属性嵌套
3. clear.css 伪元素嵌套

# demo03 混合宏
>如果你的整个网站中有几处小样式类似，比如颜色，字体等，在 Sass 可以使用变量来统一处理，那么这种选择还是不错的。但当你的样式变得越来越复杂，需要重复使用大段的样式时，使用变量就无法达到我们目了。这个时候 Sass 中的混合宏就会变得非常有意义。在这一节中，主要向大家介绍 Sass 的混合宏。

# demo04 继承等
1. 继承
2. 占位符

# demo05 插值