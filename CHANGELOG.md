# ChangeLog | 变更日志

这里是本项目文件的变更日志，不过由于本项目仓库并不是仅发布某个单独的发行版项目，所以与[通用变更日志](https://common-changelog.org)的规范会有所不同。

> [!IMPORTANT]
> 特殊规范：  
> 版本号前增加文件名作为标题： `文件名 - 版本号 - 日期`  
> 如果某一天进行了多次更新，且为同一类型，则合并至同一个二/三级标题下，其下属标题顺延增加。

## github_markdown - 2024-5-7
### [1.0.5](https://github.com/guobao2333/MT-syntax-highlight/commit/ddf18a0)
#### Fixed | 修复

1. 修复因上个版本导致的列表前无空格则不渲染的问题

#### Added | 新增

+ 添加了github的提示引用块渲染

### [1.0.4](https://github.com/guobao2333/MT-syntax-highlight/commit/39a1506)
#### Changed | 变更

* 如果分割线`<hr/>`上一行也是分割线，现在都将会渲染

#### Added | 新增

+ 新增setext标题渲染

## github_markdown - 2024-5-2
### [1.0.3](https://github.com/guobao2333/MT-syntax-highlight/commit/76c1f9a)
#### Fixed | 修复

1. 将上个版本修改处回退至1.0.0版本，以修复上个版本导致的代码块内容不渲染

### [1.0.2](https://github.com/guobao2333/MT-syntax-highlight/commit/f3f0913)
#### Fixed | 修复

1. 修复了上个版本导致的标题渲染失效

### [1.0.1](https://github.com/guobao2333/MT-syntax-highlight/commit/4411307)
#### Fixed | 修复

1. 修复了引用块背景渲染与字体渲染不一致的错误

#### Changed | 变更

* 将预览图调整至 `preview/` 目录下
* 更新和优化了文档

### [1.0.0](https://github.com/guobao2333/MT-syntax-highlight/commit/cf23fc0)

**创建了此项目仓库**👍🏻

#### Added | 新增

+ 新增语法高亮：[github规范markdown高亮](mtsx/github_markdown.mtsx)
  有关GFM的文档请看这里：[GitHub Flavored Markdown Spec](https://github.github.com/gfm)

+ 新增许可证
+ 新增`README.md`说明文档
+ 新增github markdown预览图
