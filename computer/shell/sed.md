### Sed 
#### Background
   Sed is the ultimate **S**tream **ED**itor. 

#### Sample example

#### Knowledge
##### Pattern Space
```
foreach line in file {
	//put the line into Pattern_Space
 	Pattern_Space <= line;

	// 对每个pattern space执行sed命令
 	Pattern_Space <= EXEC(sed_cmd, Pattern_Space);

 	// 如果没有指定 -n 则输出处理后的Pattern_Space
 	if (sed option hasn't "-n")  {
		print Pattern_Space
	}
}
```
##### Hold Space

##### Address

##### Reference
* [sed official website](http://www.grymoire.com/Unix/Sed.html)
* [sed 简明教程](http://coolshell.cn/articles/9104.html)

