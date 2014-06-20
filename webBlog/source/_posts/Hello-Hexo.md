title: 'Hello Hexo'
date: 2014-06-18 23:24:26
category: 
- hexo
tags: 
- hexo
- nodejs
- blog
- md
- markdown
---
這是我的第一個blog, 對於為什麼選擇[hexo](http://hexo.io)做我的blog呢？
因為這可是nodejs + markdown 所組成的blog！！
是不是很潮呀~!
廢話不多說趕快看如何啟動吧
<!-- more -->

##快速啟動

首先安裝 nvm + nodejs (ubuntu) :

###nvm

```bash
$ curl https://raw.github.com/creationix/nvm/v0.4.0/install.sh | sh
```

新增以下命令列到 `.bashrc` 的最後:

```bash
# set PATH so it includes user's private bin if it exists
if [ -d "$HOME/.nvm/bin" ] ; then
  export PATH="$HOME/.nvm/bin:$PATH"
  export NVM_DIR="$HOME/.nvm"
fi
[ -s "$HOME/.nvm/nvm.sh" ] && . "$HOME/.nvm/nvm.sh"
```

### nodejs

```bash
$ nvm install v0.10.26
```

接著安裝hexo:

###hexo

```bash
$ npm install -g hexo
```

接著只需要幾個簡單的命令, 你就可以打理好一切
```bash
$ hexo init      #初始化
$ hexo n 'title' #寫名為'title'的文章
$ hexo g         #生成
$ hexo s         #啟動, 預設為port:4000
```
真的超簡單的吧！
