## 工程效率之快捷键配置

### 背景
- 欲先攻其事必先利器

### 如何配快捷键

#### 原则
1. 不要为快捷键而配置快捷键，工具是为了更好的提高产能
2. 与自身习惯适配

#### 快捷键来源
1. 自身编程需求，在编程中经常需要哪些操作，需要鼠标点点点的，化为快捷键形成肌肉记忆
2. 吸收其他人的经验：有时候并不能察觉出自身的缺陷和编程的丑陋，需要从他人身上学习
3. 知名的工具, 尤其是鼻祖 vim, emacs，有很多功能是想不到的，需要从优秀的编辑器上学习
4. IDE的支持, idea + vscode + sublime 等, ide有的时候有些功能非常独特，好可以学习吸收

#### 关系图

![avatar](./images/short_cut_relation.svg)

#### 基本需求快捷键详解
- ps: 快捷键是不断丰富变化的过程，根据ide的支持插件的变化而变化，本篇只会介绍基本需求快捷键

#### 最常见需求描述
1. 单文件和多文件字符查找（推荐使用正则模式）
2. 单文件和多文件字符替换（推荐使用正则模式）ps: vscode的正则不是标准正则只有基本功能。
3. 打开文件 leader + k + k 
4. 定义跳转 leader + g + d (go to define)
5. 查找应用 leader + s + u (search useage)
6. 查找字快捷键 shift + *
7. vim编辑模式先ctl + a, e, d, h, j, k, l
8. 单行注释 leader + c + /
9. block注释 leader + c + b (commit block)
10. gotosymbol leader + i + i 快速查看跳转本文件symbol
11. 修改元素 leader + r + e (replace element)
12. 返回上一次光标 ctl + o
    
#### vim常见好用快捷键
1. 光标字符查找 shift + *
2. （{[<等对应端跳转 % 非常适用于前开发
3. d|v|y + i|a + {|[|(|< 块模式
4. d|y|v + f|t + 字符  字符操作
5. ctl + p|n 上下键
6. ctl + (f|b)(u|d) 上线翻页翻半页键
7. [ block 跳转 exp [ + { 跳转到 { block

#### vscode 独特优点
1. z mod模式，集中精神coding
2. expend功能： leader + x + x 可惜智能度不够建议用vim方式

#### Idea
1. 支持多文件搜索时文件名称正则
2. leader [[ | ]] method up, method down (还没找到vscode对应配置), 特别方便读代码

#### go开发建议
1. 安装插件后，开启 gopls，优点是跳转反应倍速加快，基本等于goland, 缺点耗内存

#### 进阶篇
1. 使用spaceemacsk快捷键配置
https://github.com/VSpaceCode/VSpaceCode