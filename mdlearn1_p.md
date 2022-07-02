
# markdown语法简明教程(一)

<font size=2>Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。 它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的 XHTML（或者HTML）文档。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。<p>
由于 Markdown 的轻量化、易读易写特性，并且对于图片，图表、数学式都有支持，许多网站都广泛使用 Markdown 来撰写帮助文档或是用于论坛上发表消息。 如 GitHub、Reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge、简书等，甚至还能被使用来撰写电子书。
## 在vscode中使用markdown
选择在vscode中使用markdown的原因有：
* vscode是程序员常用的软件。
* 现在有很多应用是支持markdown的，比如`typora`、`joplin`等，这些软件会有很多快捷键，还有很多交互界面，用起来肯定比vscode简单，但是这也会淡化了一些复杂的语法，所以，如果你熟悉了在vscode中使用markdown后，再接触这些笔记软件，就会非常简单。</font>
  

## 安装扩展
1. `Markdown All in One`
![pic1](pic/屏幕截图%202022-07-02%20112047.png)
<style>
    img[alt="pic1"]{
        width:200px;
        display: block; 
        margin: auto;
    }
</style>
<font size =2>安装了这个我们就可以在vscode中使用markdown了。</font>

2. `Markdown Preview Enhanced`
![pic2](pic/屏幕截图%202022-07-02%20121128.png)
<style>
    img[alt="pic2"]{
        width:200px;
        display: block; 
        margin: auto;
    }
</style>
<font size=2>这个插件是为了我们预览效果的。</font>
## 制作一个简单的md文件
1. **新建文件，记住文件后缀要是md**<p>
![pic3](pic/屏幕截图%202022-07-02%20114907.png)
<style>
    img[alt="pic3"]{
        width:200px;
        display: block; 
        margin: auto;
    }
</style>
2. **输入markdown代码**<p>
<font size =2>比如我们输入如下代码：</font>

```markdown
# markdown语法简明教程(一)

Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯（John Gruber）。 它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的 XHTML（或者HTML）文档。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。<p>
由于 Markdown 的轻量化、易读易写特性，并且对于图片，图表、数学式都有支持，许多网站都广泛使用 Markdown 来撰写帮助文档或是用于论坛上发表消息。 如 GitHub、Reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge、简书等，甚至还能被使用来撰写电子书。
## 在vscode中使用markdown
选择在vscode中使用markdown的原因有：
* vscode是程序员常用的软件。
* 现在有很多应用是支持markdown的，比如`typora`、`joplin`等，这些软件会有很多快捷键，还有很多交互界面，用起来肯定比vscode简单，但是这也会淡化了一些复杂的语法，所以，如果你熟悉了在vscode中使用markdown后，再接触这些笔记软件，就会非常简单。
```
3. **预览效果**<p>
<font size=2>我们上面安装了`Markdown Preview Enhanced`,所以我们的vscode右上角就会出现几个按钮。点击中间那个按钮就可以预览生成效果了。</font>
![pic4](pic/屏幕截图%202022-07-02%20115415.png)<p>
<style>
    img[alt="pic4"]{
        width:100px;
        display: block; 
        margin: auto;
    }
</style>

![pic5](pic/屏幕截图%202022-07-02%20131527.png)
<style>
    img[alt="pic5"]{
        width:500px;
        display: block; 
        margin: auto;
    }
</style>

1. **导出pdf文件**
<font size=2>
在预览的界面鼠标右键，`open in browser`可以用浏览器打开文件，为了生成pdf文件，在其中选择`chrome(Puppeteer)`->`PDF`就可以生成pdf文件了（这个需要你下载谷歌浏览器，然后谷歌浏览器会自带一个生成器）。
</font>
![pic6](pic/屏幕截图%202022-07-02%20132445.png)
<style>
    img[alt="pic6"]{
        width:500px;
        display: block; 
        margin: auto;
    }
</style>
## markdown语法
<font size=2>如果你学过HTML语言，那么你会发现，markdown语言和HTML差不多。</font>
### 1. <font size=5>**字体设置**</font>
#### &emsp;1.1 **字体大小**
`<font size =5>这是5号字体</font>`
<font size =5>这是5号字体</font>
<font size=2>通过修改`size`的值，可以改变字体大小，这里`size`取值是1~7,字体默认是3，也就是浏览器的默认字体大小，如果`size`的值大于7，那么就会当成7来处理</font>
        <p>
#### &emsp;1.2 **字体颜色**
`<font color=red>红色</font>`
`<font color=yellowgreen>黄绿色</font>`

    <font color=red>红色</font>
    <font color=yellowgreen>黄绿色</font><p>
    <font size=2>**也可以用十六进制表示颜色**</font>
       
    `<font color=#ff0000>红色</font>`
    `<font color=#00ff00>绿色</font>`
    `<font color=#0000ff>蓝色</font>`
        
    <font color=#ff0000>红色</font>
<font color=#00ff00>绿色</font>
<font color=#0000ff>蓝色</font>

#### &emsp;1.3 **改变字体类型**
&emsp;&emsp;`<font face="黑体">黑体</font>`
&emsp;&emsp;<font face="黑体">黑体</font>

#### &emsp;1.4 **混合使用**
&emsp;&emsp;`<font face="宋体" color=red size=5>宋体红色5号</font>`
&emsp;&emsp;<font face="宋体" color=red size=5>宋体红色5号</font>
<p>

#### &emsp;1.5 **加粗、斜体、删除线**
&emsp;&emsp;`**加粗**`
&emsp;&emsp;**加粗**
&emsp;&emsp;`_斜体_`
&emsp;&emsp;_斜体_
&emsp;&emsp;`~~删除线~~`
&emsp;&emsp;~~删除线~~

#### &emsp;1.6 **高亮文本**<font size=2>
&emsp;&emsp;可以用`来包围字符串，实现文本高亮显示如下图所示。
</font>

![pic7](pic/屏幕截图%202022-07-02%20150729.png)
<style>
    img[alt="pic7"]{
        width:200px;
        float: left;
    }
</style>
&emsp;&emsp;`我是高亮文本`
<br>
### 2. <font size=5>**标题设置**</font>
<font size=2>总共有6级标题，就通过输入多个`#`加上一个` `再加上标题内容，注意**空格**` `一定要加上。</font>
```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
![pic8](pic/屏幕截图%202022-07-02%20154101.png)
<style>
    img[alt="pic8"]{
        width:200px;
        margin:auto;
    }
</style>


### 3.  <font size=5>**区块引用**</font>
```markdown
>区块0
>>子区块1
>>>孙区块2
>>>>曾孙区块3
>>>>>玄孙区块4
>>>>>>来孙区块5
>>>>>>>晜孙区块6
>>>>>>>>仍孙区块7
>>>>>>>>>云孙区块8
```
>区块0
>>子区块1
>>>孙区块2
>>>>曾孙区块3
>>>>>玄孙区块4
>>>>>>来孙区块5
>>>>>>>晜孙区块6
>>>>>>>>仍孙区块7
>>>>>>>>>云孙区块8

### 4. <font size=5>**无序列表**</font>
```markdown
* 无序
* 无序
* 无序
```
* 无序
* 无序
* 无序

<font size=2>将`*`换成`-`、`+`也能实现无序列表。</font>
### 5. <font size=5>**有序列表**</font>
```markdown
1. 第一
2. 第二
3. 第三
```
1. 第一
2. 第二
3. 第三

<font size=2>就是数字加上`.`在加上空格` `，再加上文本就行了。
列表之间可以嵌套：</font>
```markdown
1. 第一
    * 无序
    * 无序
    * 无序
2. 第二
3. 第三
```
1. 第一
    * 无序
    * 无序
    * 无序
2. 第二
3. 第三
   
<font size=2>现在你现在能了解一些tab键的作用了吧.</font>


### 6. <font size=5>**复选框**</font>
```markdown
- [ ] 没有打勾的
- [x] 打钩的
```
- [ ] 没有打勾的
- [x] 打钩的

<font size=2>这里的`-`也可以换成`*`和`+`。
**注意里面的空格一个都不能漏，一个都不能漏，一个都不能漏。**</font>


### 7. <font size=5>**换行与tab键**</font>
<font size=2>   换行就是`<p>`和`<br>`,tab就是`&emsp;`和`&ensp;`，但是说明一点，markdown中直接敲enter或者tab键是起分割作用。也就是说`<p>`,`<br>`,`&emsp;`,`&ensp`本质是输入空字符或者空行字符，不能用来分割。
如果你现在不明白,这很正常，等你看完教程就清楚了。
如果你不熟练，我给你的建议是**尽量少敲tab键**</font>
<p>





