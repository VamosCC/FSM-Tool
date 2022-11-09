# FSM-Tool

本工程是生成有限状态机的一种方法。可以简单的通过编辑txt文件，再调用java包生成基于c++的有限状态机的代码，还支持用python脚本转换生成dot文件，再用graphviz生成状态机可视化图片。

generate c++ demo according config:
	usage: bash generateCXX -f [config_file]
	eg:
```shell
    bash generateCXX -f task.txt
```
generate  data flow diagram png according config:
	you need to install tools graphviz:
		sudo apt-get install graphviz
	usage: python tool/test.py [config_file]
	eg:
```shell
    python tool/test.py task.txt
```
