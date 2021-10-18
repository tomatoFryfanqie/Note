##### 步骤1

新建文本文件，复制以下内容，改后缀名为`.reg`，运行即可。

```
Windows Registry Editor Version 5.00
 
[HKEY_CLASSES_ROOT\.md]
@="Typora.md"
"Content Type"="text/markdown"
"PerceivedType"="text"
 
[HKEY_CLASSES_ROOT\.md\ShellNew]
"NullFile"=""
```

