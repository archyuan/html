# form 表单

 表单一般用来收集用户的信息，来和服务端进行交互。

 ## 表单常用的元素标签

 常用的元素标签有 form，input,textarea,select和option

 ## 语法

 ```<form>
      <input type="text" value="这是一个单行文本" />
      <select>
        <option>HTML</option>
        <option>CSS</option>
        <option>JavaScript</option>

      </select>
    </form>
 ```

 ## form标签的属性

 name:表单名称

 method:指定表单用哪一种HTTP提交方式

 action:指定表单数据提交到哪一个地址进行处理

 target:和a标签的target属性一样，用来指定窗口打开的方式，一般只会用到"_blank"。

 enctype:指定表单数据提交的编码方式，一般不需要设置，除非用到上传文件功能。

 ## input标签

 大多数表单都是使用input标签来实现的。

 ```<input type=-"类型" />```

 type类型有:text(单行文本),password(密码文本),radio(单选框)，checkbox(多选框),button(普通按钮),submit(提交表单数据的按钮),reset(清除表单数据的按钮),

 ### text 

 ```<input type="text"/>```

有value属性(单行文本框的默认值)，size(设置单行文本框的长度),maxlength(设置文本框最多可以输入的字符数)。

### password 

密码文本框的属性和单行文本框的属性是一样的，只不过内容是显示不出来的。

```<input type="password"/>```

### raido 单选框

```<input type="radio" name="组名" value="取值" />```

### checkbox 复选框

复选框和单选框的用法差不多

```<input type="checkbox" name="组名" value="取值"/>```

### 按钮

按钮有三种:普通按钮，提交按钮，清除按钮

```<input type="button" value="按钮" />```

```<input type="submit" value="提交按钮">```

```<input  type="reset" value="清除按钮"/>```


