# 10月30日 pm

## 快捷键
* strokeIT(mouse gesture) moom
* 滚轮切换 mousewheel


## 三角函数及图像 
* 笛卡尔坐标系，笛卡尔积 

  采用直角坐标，几何形状可以用代数公式明确的表达出来
* 极坐标 graph.tk  r=sin()
* 对数


## 通识
* 软件
* 操作系统

  软件与硬件中间的桥梁

  
	* 管理硬件
	* 对软件隐藏硬件的细节
	* 为软件提供接口以使用硬件
* 浏览器

	* 自主内核浏览器

	  壳浏览器
	* IE ->Edge/Chrome/Safri/Firefox/Opera

	  * Safari -> webkit
	  * Chrome webkit
	  * Opera 改用webkit内核

	   保持浏览器多样性有什么好处？
	  * 安卓的内核是Linux
	  * 五星浏览器

		 cutting edge/bleeding edge 尖端技术
		 shipped with bleeding edge tech
	
	* 移动端浏览器

			安卓
			IOS
			微信
	* 兼容性

			浏览器，软件，操作系统
			招聘重点从兼容性转向对新技术的了解和使用

------------------------
------------------------


# 10月31日 am

## 回顾

### 命令行界面，图形界面

### 二进制
* 模拟信号和数字信号

		消除误差
		衰减
		猫 调制解调器

### 为什么使用二进制
	 足够简单
	 足够使用
	 布尔代数为基础
	 编码

	1G 1024**3 10亿 * 8 电线
	10亿 * 2**8 状态，信息
	2**16=65536

 光盘，磁盘 ，电线

### 图片格式

* jpg JPEG

		有损压缩 渐变色 照片
		每个像素点167万种颜色 65536种颜
		2**24=1670000  3Byte
		jpg 8*8px 的小格子压缩
		视频压缩方式相同，存储差异

* png

		无损压缩 纯色 软件截图
		支持透明色（Alpha通道）
		R G B (A)
		256*256*256 = 1677万
		2**16=65536色屏幕

* gif

		动图 ，很多帧，从1670万中挑选跟原始色类似的256色
		256色颜色表 总共256色，不同图片256色不同
		原始图色不足256，为无损压缩
		支持透明 完全透明和完全不透明

* bmp

		无压缩，无损
		  16进制，写1000个数
		  winhex 查看16进制
		每个点占3个字节
		体积巨大，不适合放在网页里

* psd

  photoshop

* webp

		Google发明
		有损压缩
		各方面胜过jpg，适合移动端使用，微信图片
		支持alpha通道

# 10月31日 pm

  ## 命令行
	GUI vs CLI
	
	API

### CLI:
* Unix
* Linux 

* Win:

		cmd
		powershell

* 第三方软件：

		cgywin
		mingw
		wsl windows Subsystem for Linux

### 两个重要概念
* 当前工作目录 

		*完整路径 
		pwd (print working directory)

		*改变当前工作目录 
		cd ../.. （change directory）
		foo/bar/.../.../a/b/math.pdf(/ cli有，网页中没有)
		cd ../../windows

* 路径（列表）

		* 资源（文件）存储位置的索引

		* win与mac,linux系统路径的区别
			win分盘 使用反斜杠
			Mac，Linux使用正斜杠  
			  /study/number

		* 相对路径 relative path

		  一个路径相对于另一个路径

		* 路径的拼接

		./././a/b/math.pdf
		/././a/b/math.pdf
		foo/bar/.../.../a/b/math.pdf

### 常用命令
	cat 
	 cat a.js index.html
	pipe
	 pipe a.txt | b.txt |
	tab
	touch

* 一般命令

		pwd/cd/ls/clear/rm
* 带选项的命令

		ls -l(long) -a(all) 

		ls -l -h(human readble)
		ls -a -l -h
		ls -alh

* 将命令输出到文件

		ls > myfile.txt
		echo abc > b.txt
		echo abcd >> c.txt 追加到文件后面

*	不同系统换行符

		Linux \r 
		Mac \n  
		Win \r\n

* sodu

		(super user do)

* vim

		vimtutor 
		i esc  
		:w  :q  :q!  :wq

* 文件/文件夹相关命令

		* mkdir rmdir (a/b/c,只能删除空文件夹) rm 
		* rm -r (recursive) 递归删除，删除文件夹内所有文件
		* cp foo.png foo2.png (copy)
		* mv foo.png bar.png  改名  foo.png  ./a（文件夹） 移动
		* touch a.txt 创建文件
		* time 计算某命令运行时间  time cp InletexEMC.exe
		* date
		* cal 日历


## ASCII码
	编号 0-126 127个符号
	A： 65  a： 97  空格： 32  回车：    0：  
	0A 0D（hex） 换行

	BOM头 byte-order mark

	安装winhex

	Eascii

* GB2312 GBK 

		两个字节表示所有符号

* Unicode

		我 25105

		16进制 e6 88 

		unicode编码 utf-8 16进制 二进制 换算


--------------------------------
--------------------------------


# 11月1日 am

## 答疑

	* 编码  
		内码  
		  Unicode ascii
		输入码
		  五笔 拼音    
	* 树莓派

## 回顾
* 编码

		存储字符编号，在字体文件查找
		字体文件 vs 图片 
		矢量图（存储曲线，相当于方程？）  光栅图（存储每个像素点颜色）

* 当前工作目录

		prompt 提示符 $ 

* 路径列表

		命令对应应用程序

* 带选项/参数的命令

		简写与完整写法
		选项带值的命令 =
		将命令输出到文件 echo > 
		    追加到文件 echo >> 

* 双击代码复制运行

		gitbash  ./create


* **图片格式**

	* jpg 

			渐变色
			其它格式几乎是无损压缩
	* png 

			支持透明色
			RGB 每个像素3个字节
	* gif 

			只能存储256种颜色 选择相近的256种颜色，编号，存储编号
			动图 存储差异
			两种透明色 全透明 完全不透明
	* bmp

			无压缩，原始图像存储
			每个点占三个字节(取决于不同的存储格式 位)
			操作系统将其他格式解析为bmp及类似格式
	* webp

			移动端使用，各方面优于jpg

----
## 文本文件与二进制文件

* 文本文件

		存储符号
		ansi 图片存为文本文件 乱码
		可以用键盘编辑

* 二进制文件

		不能用文本编辑器编辑

* 图片与压缩文件拼接

## 再谈二进制

  **同余** 
	
__一个数的每一位相加能被3整除，这个数就能被3整除__

		43427 = 4*10 ** 4 + 3*10 ** 3 +4*10**2 + 2*10 + 7
		10**4 = 9999 + 1

__7天分一根金条问题 1，2，4，8，16__

	  证明是否只有一种可能 前n项和相加能够表示前 2*n-1 每一个数
   严密地证明 ??? 看视频

## 学习编程的相关文章 

http://blog.jobbole.com/22905/
https://wizardforcel.gitbooks.io/lpthw/content/57.html
http://mindhacks.cn/2011/11/04/how-to-interview-a-person-for-two-years/


我是一只编程小小鸟 刘未鹏
提问的智慧

ryanhanwu/How-To-Ask-Questions-The-Smart-Way

https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md
  
代码大全
编程珠玑

计算机程序的构造和解释
设计模式
 
* debug 的能力
* 某种编程语言是为了解决什么问题而产生的，有什么特点
* 一种无法改变你思维方式的语言是不值得学习的
* 刻意练习 每天写
* 大时间周期的练习
* 心流

		明确并且难度适当的任务
		及时的信息反馈
		面对面的交流


###  磁盘的读取
    
	间断的存储
	一圈一圈
	磁盘的悬臂
	寻道时间


# 11月1日 pm

## markdown
* 标记语言，只能表达信息，不能表达逻辑
* 内容是纯文本
* 可以是带格式文本
* 语法

	  * 最好使用4空格缩进
	  * 具体语法：文档	
		  - N级标题
		  - 段落
		  - 链接[link text](href)
		  - 图片 
		   ![](href)
	  * 加粗 
		**发表** ~~一起~~
	  * 引用 
		>
	  * 列表  
		无序列表
		  * + -
		有序列表 
		  1. 2. 3. 
	  * 代码
	     行内代码 ``
	     块级代码  
			```
			gfdssdfdd
			fdsdffdfdsda
			
			```
	 ```js
	function (a) {
	return a**2
	}
	```

		* 表格
		* 分隔线  
		---
		* 大标题


|学号|姓名|分数|
|:--:|:--:|--:|
|01|张三|100|
|02|李四|90|
   
	 * Retax
	 * UML diagrams
	 * office visio 画图
			   
1. 谷歌
	* Android 
	* YouTube
	* search
1. 苹果
	* iPhone
		 - iPhone4
		 - iPhone5
		 - iPhone4
		 - iPhone5
	* pad
	* mac
1. 香蕉


## 作业：

	用markdown抄写react的readme文档：
	https://github.com/facebook/react


## sublime
* package manager 管理插件的插件
* Emmet
* enhanced sidebar

### 多行编辑 ？？？

	* 快捷选中多个光标
	* 鼠标单击，双击，三次点击拖动以字母，单词，段落为单位选中

	* ctrl+shift + 前进/后退

* 修改配置文件 json



----------------------------

## 11月2日 am

## 答疑

* 复制图片

* 多行编辑

## 标记语言

	* markdown
	* markup

* 标记语言 **vs** 编程语言
* 标记语言

		表达内容，结构，文档
* 编程语言

		表达逻辑

* DSL

		XML eXtebsiable markup language
		MathML  
		HTML hyper text markup language
		富文本 rich text
		rtf   rich text format


## 前端的定义

		.....


## HTML

	标记语言，与md标记不同
* 标签
* 格式

		一个标签内部所有标签都闭合以后，这个标签才能闭合。
		数学符号的闭合方式

**树状结构** 

	画出树状结构 
	拿出一个完整的结构/标签，剩下的部分仍然是合法的结构。
	其它形式：书籍的目录，电脑文件夹

* JSbin




* 标签

		自闭合标签
		省略结束标签 tag omission
		* MDN HTML element

* 缩进

		两个空格
		不同层级标签之间的缩进
		文本不需要缩进
		Tab 制表符  特殊符号制表 转角符

* 标签的属性

		属性名，标签名不区分大小写，属性值区分大小写
		属性可以有多个
		属性格式：xxx="xxxx" 属性值一般使用双引号 连续字符串可以省略引号


		* title 全局属性 鼠标放在元素上才显示的文字 tooltip
		* src alt <image>  alternative
		* type <input>

  **全局属性**

	* id属性
	* name属性
	* alt属性

			指定图片加载失败时显示的文字
  * class属性 

		可以有多个类名，用空格分隔

  * tabindex 属性

		按tab的顺序
		tabindex="1" 		tabindex="2"
		tabindex="-1"

  * data-  属性

		杜撰的属性 data-isbn 
		把杜撰属性与标准属性区分开

  * contenteditable属性

		可编辑


* 转义符号

**&xxxx;**

	&quot;
	&lt; &gt;
	&amp; 

	&lt; &gt;
	&amp; 
	&#25105; 我I
	&nbsp; none-braking space  160号空格 30号空格 汉语全角空格
	pre标签 <pre> 不合并空格



	搜索转义符号 html entity
	w3fools.com
	MDN  Mozilla Developer Networ
	dev.w3.org


* 标点符号英文

		.....  



-------

# 11月2日 pm

## html标签

### 根标签 html

	开始，结束标签都可以省略

### 头部标签 head

	存储元信息

```html
<html>
 <head>
   <title>Homepage</title>
	 <meta charset="utf-8"> 元信息
	 <link rel="shortcut icon" 
	 href="favicon.ico" type="image/x-icon">
 </head>
 <body>
 </body>
</html>
```

	icon图标
	meta 元
	charset字符集
	编码方式
	  byte order字节序
		BOM
		乱码由编码方式引起
	*页面标题 
	title标签
	只有纯文字

	shortcut icon快捷方式图标
  rel (relation关系)
	favicon.ico 标签旁的图标
  
	*当前页面的样式表
	style/link 
	href hyper reference
	*视口 viewport
	<meta name="viewport" content="width=500">
	*head标签内容除标题外不会显示在页面上
	*head标签可以省略，浏览器会自动添加

### body标签

* base标签  
 基础

		*href属性 
		页面相对路径不再相对页面本身路径，而相对于base的href路径
    某些框架使用base标签
    
		*target属性
		控制a标签在当前页面打开，还是在新标签打开
		target="_blank"
		没有target属性默认在当前页面打开

		<base target="_blank">批量设置打开新的标签


### h1-h6标签

	默认标题上下有一定空格
	传统观点认为一个页面不能超过一个h1标签，为了SEO

	*SEO
	search engine optimism
	搜索引擎优化  title  h1

	提高搜索排名手段：
	*关键字
	*网页被引用数量（反向链接数量）
	  交换链接
	*使用https
	*使页面html更加语义化

### downloads属性

html5中出现的属性

	*表示点击这个链接将下载对应的文件，而不是跳转到目标页面，下载的文件名以download的属性值命名
	 `<a href="xxx/jianai.pdf" download="简爱.pdf">点我下载《简爱》完整版</a>`
	*如果同时有target="_blank",又有download属性，浏览器会怎么操作呢？
	*为什么有download这个属性呢？
	 传统浏览器中，要触发下载，需要服务器端的支持，给出特定的http头才会触发浏览器下载而不
	 是打开对应的内容
	 *这个属性的出现可以让点击下载完全由前端完成

###  p标签

* paragraph
* 段落

### a标签

* achor 锚
* 语义是一个链接，地址写在href（hyperlink reference)中

		*绝对网址，fullpath
		 `<a href="https://jd.com/>京东</a>`
		*网页内特定位置跳转地址
		 `<a href="#pos1"></a>
		*其它页特定位置跳转地址
		 `<a href="http://jd.com/#footer"></a>`
		*相对路径
		*电子邮件
		 `<a href="mailto:aaa@bbb.com"></a>`
		 `<a href="mailto:aaa@bbb.com?title=1&subject=2&content=3"></a>`
		  需要在电脑安装邮件客户端
		*电话号码
		 用在手机页面上
		*QQ/taobao 临时会话
		 tencent://temp-chat?QQ=285696737
		 thunder://xxx
		*空的href属性
		 href=""
		  链接到当前页面
			所以仅以#开头的值是中转到当前页面的特定位置
		<img src="">
		
### target属性

* 可以指定在哪个窗口打开链接
* 几个特殊值，关键字、
		
		*_blank
		链接在空白的窗口显示，也就相当于打开一个新窗口
		*_self
		其实这个是默认值，就是在当前窗体打开
		*_parent
		链接在父窗体打开显示
		*_top
		链接在顶层窗体显示
* 自定义值 


		链接在顶层窗体显示
* 自定义值 

		shoppingcart
		要求不能以_开头
		
		iframe 相关内容
		 
    
### image

	分辨率
	src
	宽高 width="300" height="400"
	alt 
	防止页面抖动
	*usemap

### span标签

* 没有语义的标签
	 <p>aaa<span>bbb</span> cccc</p>
* 一般来说想要给特定的内容添加样式时可以用一个span标签将内容包起来

### br

	*break
	*换行

### hr
  
	*horizontal
	*水平分隔线
	*自闭合标签

### font/blink/marque

	不推荐使用 deprecated
	已废弃 obsolete blink
	自动滚动
	用js模拟

### em

	强调 emphasis
	默认斜体

### strong

	强调
	比em更重（读屏软件）
	默认粗体
### bold

	只是样式加粗
	粗体

### 可访问性 accessibility

	*读屏软件
	*Windows 高对比度设置
	*aria

/

### u/i/b

	underline
	italic
	  与普通文本区分的文本
		<i></i>表示图标标签
	bold

### 注释

	*注释在HTML中没有表现出来
	会被解析
	<!-- dfasfgf-->
	*快捷键 Command + /

### pre

	*pre formatted
	*表示有预定格式的文本
	  回车会保留
	*一般与code标签连用
	 网页里显示高亮过的代码
	 <pre><code class="">

### 列表

* ul
* ol

		* 可以嵌套使用
		* li内可以嵌套任意标签
		* 多个同类项的重复应该使用列表
		* LISP List Processing SICP

		*DL description list
		dt  term,dd description
		描述性列表
  

##	作业：
抄写[css zen garden](http://www.csszengarden.com/221/)
	http://www.csszengarden.com/221/

[css 练习](https://www.w3cschool.cn/codecamp/create-a-form-element.html)
https://www.w3cschool.cn/codecamp/create-a-form-element.html
--------------------------------


# 11月5日 am

## git

		记录每一版本的内容
		记录每一次修改的差异
		
git Linux（Linux早期）

2007年公开发布

### 操作方法

		在终端中进入文件夹
		git init
		git add issue.md
		git commit -m "first commit"
		
		验证身份
		 git config --global user.email "your@example.com"
		 git config --global user.name "your name"
		 
		create mode 100644 
		-rw-r--r--@ 1 lijinyan  staff  14986 11  5 09:18 note.md
		110 100 100 不同身份权限
		6 - 4 - 4
		
		
		查看状态 git status
		
		查看差异 git diff


## 表单标签

### form

	表单字段
	表单域
	
* input 

		type
		type ="checkbox"
		type = "radio"
		type="text"
		type="password"

* action

		提交地址
		action="/login"

* target

		target="_blank"
		在新的页面打开窗口
		
* method

		表单提交方式
		
* enctype 

		编码方式
		http再谈
		
### input

	html 中能出现回车，不需要 /n
	```
	<input type="xxxx">
	
	```
type 属性的各项值
* text
* checkbox

		name属性 命名
		
* radio 

		<input type="radio" name="gender">
		<input type="radio" name="gender">
		<input type="radio" name="gender">
		<input type="radio" name="gender">
		name属性相同在同一组单选中
		
* file
	
		```
		<input type="file" accept=".jpg,.gif" name="" id="">
		
		```
		accept 过滤格式，方便用户使用
		
		input.value 只能手动设置 为了用户安全与隐私
		C:\fakepath\纯白单色.bmp

* mime type

		媒体类型
			
		accept="image/*"
		accept="image/png, .md"
		
		type/subtype:
		
			text/plain
			image/gif
			video/xxx
			application/xxx

* 其它type属性
			
		* hidden

		* button

		<input type="button">
		<button>commit</button>

		* submit

		<input type="submit">
			提交	
		* reset

		<input type="reset">

		* range

		范围

		* email

		* number,date,week,color
		
* 其它属性
	* value

		...
	
	* disabled
	
	* required
	
	* maxlength/minlength
	
			maxlength=10
			minlength=6 required
			
  * placeholder
	
  * autofocus

			光标定位
			
	* tabindex
	
	* name 
	
			<form action="https://www.google.com/search" target="_blank">
				<input type="hidden" name="newwindow" value=1>
				<input type="text" name=q>
				<input type="submit" value="Goole一下">
			</form>

* button

		<button>
		  foo 
			<font color="red">bar</font> 
		  baz
		</button>

* label

			*有for属性
			<label for="apple">男</label>
			<input type="checkbox" name="like" 
			value="apple" id="apple">

				for="btn" for="file"

			*不用for属性
			<labe><input type="checkbox" name="like" value="orange">女
			</label>
			绑定事件点两下
			
			label是非替换元素


* select

		option
		optgroup label 属性
		hgroup

		<select name="provience">
			<optgroup label="华北"> 
				<option value="" hidden selected>请选择</option>
				<option value="bj" >北京</option>
				<option value="tj">天津</option>
				<option>河北</option>
			</optgroup>
			<optgroup label="华中">
				<option value="hn" >湖南</option>
				<option value="jx" >江西</option>
				<option value="zj">浙江</option>
				<option>湖北</option>
			</optgroup>
	
* textarea

		输入多行文字
		cols="30" rows="10" 不准确，不怎么使用



----------------

# 11月5日 pm

* fieldset
  
	legend 
	
	<fieldset>
	<legend>个人信息</legend>
  </fieldset>

* 表格

		行 row
		单元格 cell
		
		<table>
			<caption>成绩单</caption>
			<tbody>
				<thead>
				<tr>
					<th></th>
					<td></td>
					<td></td>
				</tr>
				</thead>
				....
				....
				<tfoot>
				  <tr>
					  <th></th>
					</tr>
				</tfoot>
			
			</tbody>
		</table>
		
		表头放在thead里，每次翻页都会出现
		
		以前table用来做布局
		08之前 熟悉div+css布局 JD Job Description

* caption 

	表格标题
	
* thead

	表头
	
* tbody

* tr

	表行
	
* th

	表头
	
* td

		表单元格

		headers
		<td headers="num_2 name"></td> 
		对应th,读屏软件
		
		tr*3 > td{{$$}}*5
		
		<td colspan=2 rowspan=2>01</td>
		td 的跨行不能超出tbody的范围
		
		sku
		
* color

		<table border=1 cellspacing=0>
			<colgroup bgcolor=purple> 
				<col bgcolor=green>
				<col span=2 bgcolor=yellow>
			</colgroup>
			<tbody bgcolor="cyan">
				<tr bgcolor="red">
					<td bgcolor="violet">
					001
					</td>
				</tr>	 
			</tbody>
		</table>
		
* map area
  
		<body>
			<image usemap="#product-links" width=300 src="" alt="">
				<map name="product-links>
					<area shape="circle" coords="x,y,r" href=""  target="_blank" title="石榴籽">
					<area shape="rect" coords="x,y,x,y" href=""  target="_blank">
					<area shape="poly" coords="x,y,x,y,x,y" href=""  target="_blank">
				</map>
		</body>

## emmet

	ul*3>li*3>lorem

	input:radio

	table>tbody>tr*3>td*5>lorem

	ul>li*3>a+img

	ul>.foo*3
	
	div[a=b][c=d]>lorem*1000


   输入快捷写法后按tab键
	 
------------------

# 11月6日am

## 回顾

### form表单标签
* input标签

		radio name *value value="" on 
		checkbox name *value
		type="hidden" 不显示
		file accept   MIME TYPE type/subtype
		文件路径 fake 保护用户隐私
		range   min max step
		multiple type="email/file"
		disabled 禁用用户的交互
		required
		readonly
		
* textarea

		name placeholder 
		初始值放在标签中间
		
* select

		optgroup label
		option selected
		name

* fieldset

		类似colgroup/hgroup
		分组
		disabled 内部所有内容禁用
		legend 框框
		
### table

* thead tfoot

		打印每页出现表头 可以为多行
* tbody

		不打印可以忽略
* 单元格跨行受到tbody限制

		跨行左上角不动
* col 

		一列
		
* 属性

		border
		cellspacing="0"

### img

	  <img src="" usemap="#mapname">
		<map name="xxx">
			<area shape="" coords="x,y,r" href="" alt="">
		</map>
		
		shape rec circle poly
		演出选位子 看电影，火车票选位子
		
## iframe

		src
		name
		target
		frameborder=1
		添加购物车页面只出现一次
		
	<a href="http://www.csszengarden.com/221/" target="foo" frameborder=1>c</a>
	<iframe src="https://www.12306.cn/index/" name="foo" target="_blank">c
	</iframe>

		target:
		base,a,form,img+map>area
		iframe嵌套使用 target _self  _parent _top _blank
* webview 手机软件用网页实现

## frameset 
frame

```html
<frameset cols="50%,50%">
<frameset rows="50%,50%" >
	<frame src="http://www.csszengarden.com/221/">
	<frame src="https://www.12306.cn/index/">
</frameset>

<frameset rows="50%,50%">
	<frame src="https://www.12306.cn/index/">
	<frame src="http://www.csszengarden.com/221/">
</frameset>

</frameset>
```


		fallback退化方案
		degrade降级方案
		backdrop备用方案
		
		
### div 

* html5新增标签

		article
		section div
		aside
		header
		footer
		
		nav
		main
		template
			...
			...
		textarea
		
		sub
		sup
		code 
		  md ``
			经常与pre连用
		
		* script
			noscript
			<script>
			console.log('<scr' + 'ipt>')
			</script>
			
		* style
		  src
			<link>
			
		* 多媒体格式
		  *video
			```html
			<video>
			  <source src="">
				<source src="">
			</video>
			```
			controls
			
			*audio
			<audio src="" controls>
			</audio>
		
		* object
		  data
			pdf,html
		
		* embed	
    
		* canvas
		默认宽高300*150
		
		* progress
			进度条
			value max
	
		张鑫旭
		css-tricks
		
		* div,span
		  一定使用class
			
* 其它标签

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">https://developer.mozilla.org/en-US/docs/Web/HTML/Element</a>


### DTD

	Document Type Declare 文档类型声明
	文档的第一个有意义的内容

	<!DOC html>
	html 4.0 transitional
	最新标准解析页面，html5


### meta

		head标签
		head githun
		
### 语义化

		*方便人与机器的理解
		 团队易于维护
		 搜索引擎排名靠前
		*合理使用标签
		 使用合适的嵌套
		 给元素clss,id合适名称
		*css裸奔节


---------------------------------

# 11月6日pm

## role, aria-*

* accessible rich Internet Application
  (可访问的富互联网应用)
* 角色 角色状态

----------

## git


打开目录
git init
git add note.md
git commit -m "first commit"

### git 远程推送

	git init
	echo "#miao" >> README.md
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/focusor/focusor.github.io.git
	git push -u origin master