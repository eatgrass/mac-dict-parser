## 前置

* Python3
* Cmake
* Perl

## 如何使用

1. 首先准备好.mdx格式的词典文件
2. 参考`examples/ldoce5`的[notebook](https://github.com/eatgrass/mac-dict-parser/blob/main/examples/ldoce5/parser.ipynb), 将`.mdx`词库转换为Mac词典构建工具所需的[.xml](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/DictionaryServicesProgGuide/schema/schema.html#//apple_ref/doc/uid/TP40006152-CH4-SW12)
3. make && make install 编译出词典文件
4. 将词典文件拷贝至 `~/Library/Dictionaries`

## 相关文档资料

尝试自行构建之前，建议先阅读一下这些材料：

1. [mdict格式解析](https://github.com/csarron/mdict-analysis)
2. [Apple Development - Creating Dictionaries](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/DictionaryServicesProgGuide/prepare/prepare.html#//apple_ref/doc/uid/TP40006152-CH3-SW7)