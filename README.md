# bscanner
一直没有顺手的扫描器，那就自己写一个吧


# 下面是参数说明

## 必选参数：

-u 扫描目录  
--test 测试，现在默认扫描http://www.wooyun.org(我随便打的，别打我)

## 可选参数：

-t,--thread   线程数，默认为30，可选(1~50)
-e,--ext  是否使用文件类型拓展，默认为关闭，现在的拓展为['.bak','.orig','.inc','.swp','~']
-f,--filename  字典拓展，默认为./dic/php.txt

