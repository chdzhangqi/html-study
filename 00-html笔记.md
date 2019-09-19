## HTML标签
### 1. 四个基础的标签
- html
- head
    - title
- body
### 2. 排版标签
- h1(max)，一般在logo使用，其他地方不使用。
- h6(min)，h标签带换行。
- p(段落标签)，p标签带换行。
- hr(几乎不用，使用div来代替)。
- br。
- div，霸道独占一行。
- span，可以和别人占据一行。
### 3. 文本格式化
- strong(加粗)，推荐
- b(加粗)
- i(倾斜)
- em(倾斜)，推荐
- s(删除线文字)
- del(删除线文字)，推荐
- u(下划线)
- ins(下划线)
### 4. 标签的属性(不推荐使用，使用css完成)
### 5. 图像标签
- img src="" alt=""
    - alt
    - title
    - width，height 一般情况选择改变一个就行，会等比例缩放。
    - border
### 6. 链接标签
- a
    - target="_blank"，在新的窗口打开一个网页。
    - target="_self", 在当前窗口打开。
    - base标签让整个页面的a标签都是以新的窗口打开。
    - 外部链接
        - href 中必须添加http://
    - 内部链接
        - href 内部连接不需要加http
        - 锚点
### 7. base标签

### 8. 特殊字符打开
- &nbsp; 空格
- &lt; 小于符号
- &gt; 大于符号
- &copy; 版权符号

### 9. 注释标签

### 10. 相对路径和相对路径
- 相对路径：
    - ./  当前文件夹
    - ../ 上一层文件夹
    - xx/ xx文件夹下面的
- 绝对路径：

### 11. 列表便签
- ul、li 无序便签
- ol、li 有序标签
- dl、dt、dd自定义列表(用来做网页的底部)

### 12. 表格
- 表格不是用来布局的，用来显示大量数据的。
- tr是行，td是单元格的标签
- th和td的区别是：th有居中和加粗和垂直。
- caption 表格的标题
- 表格的属性
    - border
    - cellspacing:不写的默认是2，是单元格和单元格之间的距离。
    - cellpadding：单元格和里面文字的距离。默认是1
    - width
    - height
    - align: 在网页中的水平对齐，left，rgiht，center
    - colspan、rowspan：跨行和跨列合并

### 13. 表单标签
- 表单控价
    - input: type属性(text, submit, password, button, radio, checkbox, reset, image, file);value属性; name属性; 
    - 默认选择项: checked = "checked"
    - size
    - maxlength
    - placeholder
- label标签，可以直接获取控件的焦点，直接包裹input，多个input也可搞定，使用，for和id
- textarea
- select：option；selected = "selected"
- form：method、action

### 14. html5新特性
- header
- footer
- nav(导航栏信息)
- article(文章)
- section(文章中的小节)
- aside(侧边)))
- datalist option
- fieldset 和 legend 搭配使用
- html5 
    - type
        - email, tel, url, number, search, range, time, date, month, week
    - 添加的属性
        - placeholder, autofocus, multiple, autocomplete(表单自动填充), required(必填项), accesskey(获取焦点)
    - 多媒体标签
        - embed(现在使用)
        - audio
        - video