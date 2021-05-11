VIM常用技能
-----------------

## VISUAL模式

### 多行代码注释取消注释

#### 不借助插件的方式

1. CTRL + v 进入可视化模式(visual block)，选择要被注释的代码前的一列
2. 按大写`I`进入插入模式(insert model),输入注释符号
3. 按ESC键退出
4. 删除多行注释的方法，同样 Ctrl+v 进入列选择模式，移到光标把注释符选中，按下d，注释就被删除了。

**缺点: 取消注释的时候，注释符号必须在同一列内**

#### 插件

- Plugin 'scrooloose/nerdcommenter'

## INSERT模式

### 代码补全

#### VIM自带代码补全

Omni Completion

[插件地址](https://www.vim.org/scripts/script.php?script_id=3172)

插入模式下快捷键: CTR + x + o
缺点：不能输入及时提示
