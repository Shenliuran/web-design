# 第三章 初探HTML

## 创建HTML文档

+ 有些元素为空时没有意义（如`code`就是其中之一），即便如此，它也是有效的HTML代码，更有效的表示方法是：`</code>`
+ 只能使用一个标签表示的元素被称为 **虚元素**，如`<hr>`，第二种写法是：`<hr />`（本书采用的写法）
+ HTML文档的外层结构：

    ```html
    <! DOCTYPE HTML>
    <html>
        <!-- elements go here-->
    </html>
    ```

+ `head`元素内部是元数据，如`title`
+ 常用的HTML实体：
    >字符|实体名称|实体编号
    >|:--|:-----|:-----|
