###first recoding

- download filezer
- download vscode
- download wechat
- download cloud music
- download idea
- download eclipse
- download git
- download htop
- download ssr.deb (sudo dpkg -i electron-ssr-0.2.6.deb) 
- download uget+aria2

### vim 配置
[插件一comment-](https://github.com/wincent/command-t/blob/master/doc/command-t.txt)
[vim配置](www.jianshu.com/p/0a3508fde49d)

### python问题
```
deepin vim默认是不支持的，所以得从官网github上下载重新编译就OK。
```

### vscode 配置Python和c++
```
具体看我上传的四个文档OK。

```
### eclipse和idea配置就不用我多说了

[上传代码参照这个链接](https://cloud.tencent.com/developer/article/1387671)

```

t                                                                                                                                      
  2 
    3 [参照这个链接](https://cloud.tencent.com/developer/article/1387671)
	  4 ```
	    5 首先将远程仓库和本地仓库关联起来：
		  6 
		    7 git branch --set-upstream-to=origin/master master
			  8 
			    9 然后使用git pull整合远程仓库和本地仓库，
				 10 
				  11 git pull --allow-unrelated-histories    (忽略版本不同造成的影响)
	 12 
	  13 完成，问题解决

```

```
Linux中vim自动补全python提示（pydiction）

1、下载pydiction文件
# wget https://github.com/rkulla/pydiction/archive/master.zip

2、解压zip文件，解压后出现“pydiction-master”目录（如果没有unzip命令，安装unzip：yum install unzip）
# unzip master

3、创建目录
# mkdir -p ~/.vim/tools/pydiction

4、将“pydiction-master”目录中的文件复制到“~/.vim”目录下
# cp -r pydiction-master/after ~/.vim
# cp pydiction-master/complete-dict ~/.vim/tools/pydiction

5、建立“.vimrc”文件
# touch ~/.vimrc

6、编辑“.vimrc”文件（# vim ~/.vimrc ）添加如下内容
filetype plugin on
let g:pydiction_location = '~/.vim/tools/pydiction/complete-dict'
```
### 接下来就特牛了，利用vim进行前端开发
- 插件一（emmet-vim）
[参考链接](https://github.com/mattn/emmet-vim)

- 插件二 查询功能（ctrlp.vim）有墙
[参考链接](http://kien.github.io/ctrlp.vim/)

- 插件三 智能提示功能(neocomplete.vim)
[参考链接](https://github.com/Shougo/neocomplcache.vim)

- 忘了参照下面blog
[参考blo](https://www.cnblogs.com/lxg0/p/vim.html)

