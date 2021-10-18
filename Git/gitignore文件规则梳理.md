#### gitignore文件规则梳理



**需要在push之前写好.gitignore文件，否则规则不起作用**

过滤规则：

`/out/` 	过滤整个out文件夹

`*.idea`	过滤后缀为.idea的所有文件

`/out/test.java` 过滤out文件夹的test.java文件

添加规则：

`!/out/test.java` 只添加out文件夹下的test.java文件



语法：

以 `/` 开头表示目录

`*` 代表通配多个字符

`?` 代表通配一个字符

`!` 表示不忽略