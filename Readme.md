## 前置

Python3
Cmake

## 如何使用

1. 首先准备好.mdx格式的词典文件
2. 参考`examples/ldoce5`的notebook,  将.mdx文件转换为 .xml文件
3. make && make install 编译出词典文件
4. 将词典文件拷贝至 `~/Library/Dictionaries`


## 相关文档资料

1. [mdict格式解析](https://github.com/csarron/mdict-analysis)
2. [Apple Development - Creating Dictionaries](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/DictionaryServicesProgGuide/prepare/prepare.html#//apple_ref/doc/uid/TP40006152-CH3-SW7)