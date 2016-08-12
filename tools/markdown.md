# Markdown极简教程 

---
本教程将采取**内容与形式一体化**的方式进行。具体来说，从本段开始，正文分为多个段，**奇数段**为实际显示内容，其紧邻的**偶数段**为奇数自然段内容对应的Markdown形式，奇数偶数段间以分割线分割。偶数段可为Markdown代码，因此以`代码`显示，把偶数自然段的内容直接拷贝到支持Markdown的编辑环境中，即可显示对应奇数自然段。[Markdown](https://en.wikipedia.org/wiki/Markdown)编辑环境如喜欢在浏览器中编辑，可用[简书](http://www.jianshu.com/)，喜欢软件工具形式的，在Windows下可用[MarkdownPad](www.markdownpad.com)，ios下可使用[Mou](http://25.io/mou/)。建议边看本教程边动手拷贝修改。

---
  
``
本教程将采取**内容与形式一体化**的方式进行。具体来说，从本段开始，正文分为多个段，**奇数段**为实际显示内容，其紧邻的**偶数段**为奇数自然段内容对应的Markdown形式，奇数偶数段间以分割线分割。偶数段可为Markdown代码，因此以`代码`显示，把偶数自然段的内容直接拷贝到支持Markdown的编辑环境中，即可显示对应奇数自然段。[Markdown](https://en.wikipedia.org/wiki/Markdown)编辑环境如喜欢在浏览器中编辑，可用[简书](http://www.jianshu.com/)，喜欢软件工具形式的，在Windows下可用[MarkdownPad](www.markdownpad.com)，ios下可使用[Mou](http://25.io/mou/)。建议边看本教程边动手拷贝修改。
``

---
# Markdown极简教程
## 欢迎转载，本文链接：
### https://www.gitbook.com/book/4078/ability_tools/details
---
#内容提纲
- **段落中的文本**
 - 改字体
 - 添超链接
 - 转义字符
- **图片、公式与表格**
  - 插入图片
  - 插入公式
  - 插入表格
- **引用**
***
- **段落中的文本**
 - 改字体，示例：**粗体**，*斜体*，~~删除~~
 - 添超链接，示例：[本教程链接](https://www.gitbook.com/book/4078/ability_tools/details)
 - 转义字符，想输出用于Markdown标记的字符，而不是要用这些字符标记，可前面加`\`符号。示例：\`\`, \[\], \-, \*, \\等等。
---
- **图片、公式与表格**
  - 插入图片，示例：![图片](http://daringfireball.net/graphics/logos/)
  - 插入公式，公式编写采用Latex格式（Latex数学公式的[最简教程](https://4078.gitbooks.io/ability_tools/content/tools/latex_equ.html)），然后将Latex公式放在4个连续$符号的中间即可。如：$$ x^2 $$，如：$$ \lim_{n \rightarrow +\infty} \frac{1}{n(n+1)} $$
 - 插入表格
 用字符`-`与`|`排成表格，但注意第一行最好没有空格，线可以不用太对齐，示例：
 
AB | ED 
--- |--
  a   | b    
  d    | e    
---
 - 引用，示例：
 
> 引用的文字从此行开始
>>再次引用，注意空行的作用
>>
>>>三次引用，`还可以插入代码`，公式$$s^2$$等。注意
>>>如没空行，则文本与上一行连上了。

---
更多Markdown的知识，可参考[Markdown语法](http://www.appinn.com/markdown/)，或直接搜索。