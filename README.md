Config your vim from mine:
==============



安装
--------------

Note: this document is only tested on Ubuntu(trusty).

### Step 1
```shell
sudo aptitude install -y exuberant-ctags
```

### Step 2
```shell
cd ~ && git clone https://github.com/yanyingwang/.vim.git
```

#### Step 3
```shell
vim
```

If nothing happen, type command below in the vim:
```shell
:NeoBundleInstall!
```
* NeoBundleList - list configured bundles
* NeoBundleInstall(!) - install (update) bundles
* NeoBundleClean(!) - confirm (or auto-approve) removal of unused bundles

After install Unite.vim:
* Unite neobundle/search - list configured bundles
* Unite neoBundle/install - install bundles
* Unite neoBundle/update - update bundles
* Unite neoBundle/clean(!) - confirm (or auto-approve) removal of unused bundles

### Step 4
So easy! Rock your vim, now!!!




 

说明文档
--------------

### Vim自定义功能
* zh zl 在buffer之前左右跳转
* th tl 在tab之前左右跳转
* 搜索完成后，按空格键取消高亮
* W! 命令强制sudo写入文件

### unite.vim
我的vim配置严重依赖于unite插件及其衍生插件。


### Unite相关快捷键列表(on normal mode)   

| 命令 | 映射命令 | 作用 | 触发快捷键之后的快捷键说明 |
|:-----------|:------------:|:------------:|:------------:|
| ff | Unite file | 打开文件浏览 | Q,q退出，i进入插入模式， r重命名文件，N新建文件, d删除文件, '进入快速打开文件模式-再按<C-c>则退出此状态
| fb | Unite buffer | 打开unite buffer | d关闭选中buffer
| ft | Unite tab | 打开unite tab | none
| fv | VimFiler | 打开文件浏览高级 | K新建目录
| fh | VimShell | open VimShell | esc进入normal mode
| fu | UniteResume | 恢复上一次Unite操作(open Unite file if last opration is it) | none
| fr |  none | 依次搜索文件 | none
| frw | none | 依次搜索文件，根据当前光标高亮文字 | none
| fp | Unite process | 查看进程 | | /开始搜索，d杀掉进程
| fc | none | 打开当前编辑文件目录 | none
| fj | Unite jump | 再文件编辑历史里面选择要打开的文件 | none
| fm | Unite bookmark | 打开书签 | d删除标签
| fma | none | 增加书签 | none
| fg | Unite grep:. | 从cd目录处开始搜索代码 | none
| fgw | Unite grep:. | 从cd目录处开始搜索代码，以当前光标处文字为搜索内容 | none
| f/ | Unite grep:. | 从自定义目录处开始搜索代码 | none
| f/w | Unite grep:. | 从自定义目录处开始搜索代码，以当前光标处文字为搜索内容 | none
| fo | Unite outline | 查看当前文件的代码结构，并快速跳转 | none
| fa | Unite source | 查看unite的所有命令，并可选择执行 | none





