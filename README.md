# HTML常用标签
以博客记录我在HTML重难点课程中的心得。

本次课程中，方老师为我们讲解和HTML中常用的几个标签。
## a 标签
### a 标签的属性
 * href：主要表示的时超链接，是用户在点击该a标签后跳转至href所在地址。
    通常来说，其取值可以分为：网址、路径、伪协议以及id等。
    通常来说
    1. 网址：当a标签的href取值为网址时，如果用户点击这一标签，那么用户将会跳转至该网址。
    2. 路径：跳转至该路径下存放的文件
    3. 伪协议：通过取值为伪协议（例如：mailto:邮箱、tel：手机号），可以跳转至发送邮件界面或拨号界面。
    4. id：用于跳转至本页的某一部分。
* target:主要是用于确认在点击a标签后，加载链接资源的位置。
    1. _blank：在新窗口加载。
    2. _top：在顶层中加载。
    3. _parent:在当前HTML浏览上下文的父浏览中加载。
    4. _self:在当前页面加载。
    5. window的name或iframe的name：在程序员命名的name中加载。
* download：用于下载页面，但也存在并非所有浏览器都支持的问题。
## iframe标签
iframe标签用于内嵌窗口，但现在已经很少使用。
## table标签
作用通常是创建一个表格。在table标签中通常包括table、thead、tbody、tfoot、tr、td、th等标签。
* tr：table row，表示表中的一行。
* th：table head，表示表中的表头。
* td：table data，表示表中的内容。
### table的相关样式
* table-layout：通常取值有auto、fixed。auto：根据内容确定每列的宽度。fixed：使格列尽量等宽。
* table-collapse：通常取值为collapse，用于确定表格是否合并。
## img 标签
作用是发出get请求，展示一张图片。
### img标签的属性
* src:图片地址。相对路径或绝对路径军均可。
* alt：如果图片加载失败，那么就代替显示alt的内容。
* width和height：用于制img的宽高。当只指定其中一项时，另一项会自适应。若两项同时指定，那么可能会导致图片变形。
### img标签的事件
* onload和onerror：表示调用成功和调用失败。
### img标签的响应式
* max-width：100%。使图片宽度等于页面宽。

## form标签
作用使发get或post请求，然后刷新页面。
### form标签的属性
* action:一个处理此表单信息的程序所在的URL。
* autocomplete：确定自动填充的内容。
* target：与a标签的target相似。
### form标签的事件
* onsubmit：当用户提交时，就会触发。# notes-of-HTML-2
