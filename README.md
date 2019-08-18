# 沪江终端词典  
[![](https://img.shields.io/github/license/asutorufa/hujiang_japanese_dict.svg)](https://raw.githubusercontent.com/Asutorufa/hujiang_japanese_dict/master/LICENSE)
[![](https://img.shields.io/github/release/asutorufa/hujiang_japanese_dict.svg)](https://github.com/Asutorufa/hujiang_japanese_dict/releases)
![GitHub top language](https://img.shields.io/github/languages/top/asutorufa/hujiang_japanese_dict.svg)

运行:
```shell
npm install
# 日语
node hjjp.js <word>
# 英语
node hjen.js <word>
```
可以链接到~/.local/bin直接运行:
```shell
ln -s $(pwd)/bin/hjjp ~/.local/bin/hjjp
hjjp 東京
ln -s $(pwd)/bin/hjen ~/.local/bin/hjen
hjen hello
hjen 你好
```

打包:
```shell
npm install
npm run pkg 
```

使用方法:  
```
# 日语
node hjjp.js 東京
# 英语
node hjen.js hello
node hjen.js 你好
```

![](https://raw.githubusercontent.com/Asutorufa/hujiang_japanese_dict/nodejs/hj_dict.png)  
**查词结果均来自 沪江小d网页版**
