# markdown-notes
### 有关markdown的笔记
---
==（1） 标签==

# 一级标签
## 二级标签
### 三级标签
#### 四级标签
##### 五级标签
###### 六级标签

==（2）字体==

**加粗**
*倾斜*
***斜体加粗***
~~删除线~~
==高亮==
我是^上标^
我是~下标~

==（3）列表==

+ 一二三四五
	+ 上山打老虎!
		+ 老虎打不到
			+ 打到小松鼠
1. 一二三四五
2. 上山打老虎
3. 老虎打不到!

4. 打到小松鼠

==（4）表格==

| MON | TUE | WED | THU | FRI |
| :--: | :---: | :---: | :---: | :-: |
| 上山 | 上三 | 上山 | 上三 | 上山 |
| 打老虎 | 大兔子 | 大包子 | 大松鼠 | 打哈切 |

==（5）引用==

> 一二三四五
> > 上山打老虎
> > > 老虎打不到
> > > > 打到小松鼠

==（6）分割线==

---

==（7）代码==

`这是一段代码`
```python
for i in range(0, 20):
    print("hello markdown!!!")
```
```c++
for (int i = 0; i < 10; i++ ) {
	std::cout << "hello markdown!!!" << std::endl;
}
```
==（8）公式块==

$$
E = MC^2
$$

==（9）任务列表==

- [ ] 这是第一个任务

- [ ] 这是第二个任务

- [x] 这是第三个任务

==（10）链接引用==

==（11）内容目录   (点击会跳转)==

[TOC]

==（12）内联公式==

$a^2+b^2=c^2$

==（13）注释==

<!--这是一段注释-->

==（14）超链接==

[这是一段跳转到百度的超链接](www.baidu.com "百度" )
<https://markdown.com.cn>  
<freeberalan@gmail.com>  
这是一段强调**[链接](https://ef.org)**  
这是一段倾斜*[链接](www.markdownguid.org)*  
这是一段页面内跳转[`链接`](#code)  
请点击[百度][1]。。。。。  
这是一个[脚注][^script]。。。。。  

[1]: www.baidu.com	"这是百度的链接"
[^script]: 这里是脚注
 
==（15）图片==

![美人儿](https://img.win3000.com/m00/fb/10/8d10e6721bdc02c3faf5c863f8d76086.jpg?down)

<img src="https://img.win3000.com/m00/66/24/7b27fc1ad5c860830ca52df7a2619a9f.jpg?down" alt="CSS样式图片" style="width:50%; border:2px solid RGB(240, 240, 240); border-radius:10px; box-shadow:0px 0px 10px 2px RGBA(0, 0, 0, .5)" />

==（16）html==

<div style="display: flex;flex-allow: row nowrap;justify-content: space-between; align-items: center; width: 100%; background-color: yellow">
    <div style="height: 100px; width: 100px; background-color: red; text-align: center; line-height: 100px">左红</div>
    <img src="https://img.win3000.com/m00/0d/99/1cad4993f0f6bff57333ab737a29f691.jpg?down" alt="CSS样式图片" style="width:50%; border:2px solid RGB(240, 240, 240); border-radius:10px; box-shadow:0px 0px 10px 2px RGBA(0, 0, 0, .5)" />
    <div style="height: 100px; width: 100px; background-color: green; text-align: center; line-height: 100px">右绿</div>
</div>


==（17）键盘按钮==

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

