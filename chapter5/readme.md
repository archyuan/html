# 列表 

## 有序列表 

 有序列表的各个列表项都是有顺序的，一般采用数字或者字母作为顺序，默认采用数字顺序。 

 ```<ol><li>列表项1</li><li>列表项2</li><li>列表项3</li></ol>```


 可以使用type属性来改变有序列表用什么来表示顺序。

 常用属性取值有 

 ```1,a,A,i,I```

在css中可以用```liststyle-type```属性来代替type属性。

## 无序列表 

无序列表没有一定的顺序，默认情况下无序列表的列表项符号是```●```。也可以用type属性来改变表示的符号。如
'disc'实心圆，'circle'是空心圆，'square'正方形。

```
<ul type="circle">
                  <li>列表项1</li>
                  <li>列表项2</li>
                  <li>列表项3</li>
</ul>
```
## 定义列表 

定义列表由两部分组成：名词和描述。如，

```
<dl>
  <dt>HTML</dt>
  <dd>制作网页的标准语言，控制网页的结构</dd>
  <dt>CSS</dt>
  <dd>层叠样式表，控制网页的样式</dd>
  <dt>JavaScript</dt>
  <dd>脚本语言，控制网页的行为</dd>
</dl>
```

dl是definiton list,dt是definition term,dd是definition description。

实际开发中，定义列表比较少用，在某些高级列表中也会用到(如自定义表单)

