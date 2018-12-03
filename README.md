# use_codecs


使用python的codecs包解决linux中文件传输到windows的csv乱码问题

在使用codecs.open("a.txt",'w','gbk')时可能出现有些字符无法识别等问题

使用ignore字段忽略无法识别的字符可以解决改问题
