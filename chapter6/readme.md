# 表格

 表格一般由以下三个部分组成。

 1. table标签
 2. 行,tr标签(table row)
 3. 单元格,td标签(table data cell)

 ```
 <table>
   <tr>
     <td>单元格1</td>
     <td>单元格2</td>
   </tr>
   <tr>
    <td>单元格3</td>
    <td>单元格4</td>
   </tr>
 </table>
 ```

 # 表格的完整结构 

 ## 表格标题 caption
  表格一般都有一个标题，可以使用caption标签来实现。
  ```
  <table>
    <caption>表格标题</caption>
    <tr>
     <td>单元格1</td>
     <td>单元格2</td>
    </tr>
    <tr>
     <td>单元格3</td>
     <td>单元格4</td>
    </tr>
  </table>
  ```

  ## 表头单元格
   单元格有两种，一种是“表头单元格”，使用th标签；一种是“表行单元格”使用td标签。

```
<table>
 <caption>表格标题</caption>
 <tr>
  <th>表头单元格1</th>
  <th>表头单元格2</th>
 </tr>
 <tr>
  <td>表行单元格1</td>
  <td>表行单元格2</td>
 </tr>
 <tr>
  <td>表行单元格3</td>
  <td>表行单元格4</td>
 </tr>
</table>
```

表头单元格在显示上会以“粗体”和“居中”来显示th标签中的内容，但是td不会


## 表格的语义化(区域划分)

 为了更好的将表格内容的语义化和区域的划分，HTML加入了thead,tbody,tfoot3个标签。使其更具有可读性和可维护性。

 ```
 <table>
  <caption>表格标题</caption>
  <!--表头-->
  <thead>
    <tr>
      <th>表头单元格1</th>
      <th>表头单元格2</th>
    </tr>
  </thead>
  <!--表身-->
  <tbody>
    <tr>
      <td>表行单元格1</td>
      <td>表行单元格2</td>
    </tr>
    <tr>
    <td>表行单元格3</td>
    <td>表行单元格4</td>
    </tr>
  </tbody>

  <!--表脚-->
  <tfoot>
   <tr>
    <td>表行单元格5</td>
    <td>表行单元格6</td>
   </tr>
  </tfoot>
 </table>
 ```


 ## 单元格的合并

 ### 行合并(rowspan)

 行合并: 将纵向的N个单元格合并

 ```<td rowspan="跨域的行数"></td>```

 ```
 <table>
  <tr>
   <td>姓名：</td>
   <td>小明</td>
  </tr>
  <tr>
   <td rowspan="2">喜欢水果:</td>
   <td>苹果</td>
  </tr>
  <tr>
   <td>香蕉</td>
  </tr>
 </table>
 ```

 ### 列合并

 将横向的N个单元格合并

 ```<td colspan="跨域的列数"></td>```

 ```
 <table>
  <tr>
    <td colspan="2">前端开发技术</td>
  </tr>
  <tr>
   <td>HTML</td>
   <td>CSS</td>
  </tr>
  <tr>
   <td>JavaScipt</td>
   <td>jQuery</td>
  </tr>
 </table>
 ```