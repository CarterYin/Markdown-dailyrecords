# <font face="仿宋" color=orange>CarterYin 的 Markdown 学习笔记之入门篇</font>
## <center><font face="楷体" size=5>CarterYin</font></center>
##### 资源主要来源于B站【【全网最详细Markdown入门使用教程】40分钟教会你用免费的vscode做出好看的笔记】https://www.bilibili.com/video/BV1bK4y1i7BY?vd_source=4fd6c4265e65c0785c912874692a3971
##### 本人进行了一些修改

### 一、安装必要插件
  - Markdown all in one
  - Markdown Preview Enhanced
  - Markdown PDF
  - Paste Image
  
### 二、创建与编辑
  **创建.md文档，打开同步预览功能（在vscode右上角一个书页加上放大镜的图标，单击即可），开始编辑。**

### 三、基本语法
1. **标题**
#一级标题 
##二级标题
等等（最多支持6级标题）

2. **引用**
   > citation
   >> citation嵌套(需要和上面对齐，否则会有下面的效果)

   > citation
>>citation

3. **列表**
   1. 无序列表
   - 列表1
   + 列表2
   * 列表3
   2. 有序列表
   3. 嵌套
   4. TodoList
     - [x] a
     - [ ] b
     - [ ] c 
  
4. **表格**
   | 左对齐 | 居中对齐 | 右对齐 |
   | :----- | :---: | ----: |
   | a | b | c | 
   | c | d | f |

5. **段落**
- 换行？—— 两个以上空格后回车/空一行  
- 分割线 —— 三个以上*，
  ***
  ****
- 字体
  | 字体 | 代码 |
  |:--:|:--:|
  |*斜体*|* *|
  |==高亮==|== ==|
  |**粗体**|** **|
  |***斜粗体***|*** ***|
  |~~删除~~|~~ ~~|
  |<u>下划线</u>|``` <u> </u>```|

  (```的功能下面会提到)

  - 脚注
  CarterYin's note for Markdown[^1]  
  这里的```[^1]```在下面必须要有呼应，不然就不会出现脚注的符号。

6. **代码**
   ```
   #include<iostream>
   using namespace std;
   int main(){
    print("Hello world!")
   }
   ```
   `print("Hello world!");`

7. **超链接**
   - [更多使用教程可以参考网站]；https://www.markdown.cn/docs/cheat-sheet
   https://markdown.com.cn/basic-syntax/
   https://www.runoob.com/markdown/md-link.html

   - 查看更多使用功能请[点击链接][教程]
   - 上面的教程和脚注一样要在文末注释具体链接。

8. **图片**
- 使用图床保存图片并实现插入
  [路过图床]:https://imgse.com/
- 使用markdown语法插入
[![pFZHwAe.jpg](https://s11.ax1x.com/2024/01/23/pFZHwAe.jpg)](https://imgse.com/i/pFZHwAe)

- 使用HTML语言实现调整图片大小和位置功能
<a href="https://imgse.com/i/pFZHwAe"><div
align=center><img src="https://s11.ax1x.com/2024/01/23/pFZHwAe.jpg" alt="pFZHwAe.jpg" border="0" width="80%" height="60%"/></div></a>


### 四、其它操作

**插入latex公式**
- 行内显示公式：
  $f(x)=ax+b$
- 块内显示数学表达式：
$$
\begin{Bmatrix}
a & b\\
c & d
\end{Bmatrix}
$$

- **html/css语法**
  - ctrl+shift+p 搜索 "Markdown Preview Enhanced Customsize CSS"在style中使用css语法改标题格式等
  
```
.markdown-preview.markdown-preview {
  // modify your style here
  // eg: background-color: blue;
  h1 {
    text-align:center;     // 一级标题居中
  }
}
```

- **个性化设置**
  File-Preferences-Settings找到markdown对应的部分，进行个性化设置。


### 五、导出为pdf文档

- 使用Markdown PDF(不推荐，原因是格式问题，以及公式等无法呈现)
- 右键单击预览的.md文件，选择Open in Browser，在浏览器里右键另存为PDF(本人电脑尝试了不行，另存为pdf之后无法打开pdf文件)(于是本人建议借别人电脑搞)
- 经舍友帮助，发现另外一款好用的软件叫Typora,支持导出为PDF且没有格式错误。



[教程]:https://www.markdown.cn/docs/cheat-sheet
[^1]:芜湖！  

