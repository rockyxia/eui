# EUI
常用基础、扩展性高的CSS模块库<br><br>
EUI是基于<a href="https://github.com/rockyxia/base/" target="_blank">base.css</a>添加了HTML元素的布局和样式，以及常用的UI组件。EUI提供最基础的样式，具有很高的扩展性，鼓励你基于此写出自己的样式。
# 使用EUI
具体使用方法及说明可以去<a href="http://rockyxia.github.io/eui/" target="_blank">EUI网站</a>查阅，很容易就能上手使用。
# EUI演示源码结构
> **EUI**<br>
> |- **css**<br>
> |- -> eui.css <code>未压缩的完整版EUI样式表</code><br>
> |- -> eui-form-beautify.css <code>未压缩的表单美化样式表</code><br>
> |- -> eui-form-beautify-min.css <code>压缩的表单美化样式表</code><br>
> |- -> eui-min.css <code>压缩的完整版EUI样式表</code><br>
> |- -> main.css <code>EUI演示网站的样式表</code><br>
> |- **images**<br>
> |- -> link-icon.png <code>链接图标</code><br>
> |- **js**<br>
> |- -> jquery.selectbeautify.js <code>表单美化的Javascript文件</code><br>
> |- **sass**<br>
> |- -> _base.scss <code>浏览器效果统一基础样式源码</code><br>
> |- -> _button.scss <code>按钮样式源码</code><br>
> |- -> _customize.scss <code>统一定义样式表</code><br>
> |- -> _form.scss <code>表单样式源码</code><br>
> |- -> _form-beautify.scss <code>表单美化样式源码</code><br>
> |- -> _menu.scss <code>菜单样式源码</code><br>
> |- -> _table.scss <code>表格样式源码</code><br>
> |- -> eui.scss <code>EUI统一引入文件</code><br>
> |- -> main.scss <code>EUI演示网站的样式源码</code><br>
> |-> demo.html<br>
> |-> favicon.ico<br>
> |-> index.html<br>
> |-> README.md<br>

# 更新日志

## V0.2.0@20161214
> * [改]表单美化模块v0.1.2(Select居中调整)
> * [改]表单模块v0.1.2左右式布局的label与表单美化模版的label样式冲突处理
> * [增]增加常用布局模式，也是由于从基础向应用的转变，版本号升级为v0.2.0
> * [增]增加网页制作常用插件列表


## V0.1.2@20161202
> * 表单美化模块v0.1.1(增加Select、Input[type=file])
> * 表单美化模块v0.1.1的CSS单独生成了一个供独立使用
> * 常用布局的计划排出

## V0.1.1@20160830
> * 新增表单美化模块v0.1.0(包括Checkbox、Radio)
> * 按钮模块优化v0.1.1
> * 表单模块优化v0.1.1

## V0.1.0@20160701
> EUI（v0.1.0），包括按钮、表单、表格、菜单四个基础模块。