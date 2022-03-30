# my_blog

这是我的第一个前端项目，用react写一个博客。

边写边学边改进。



## Update Log

| 事件序号 | 时间       | 事件                                                         |
| -------- | ---------- | ------------------------------------------------------------ |
| 0        | 2022/02/26 | 用react-router v6作为路由                                    |
| 1        | 2022/02/27 | 将主要组件由类组件转为函数组件                               |
| 2        | 2022/02/28 | 完成项目主要静态页面。                                       |
| 3        | 2022/03/01 | 学习函数式组件下react-redux的使用                            |
| 4        | 2022/03/05 | 完成react-redux管理github issues数据                         |
| 5        | 2022/03/07 | 完成文章页面，使用react-markdown渲染页面                     |
| 6        | 2022/03/08 | 完成右侧分类列表、标签列表、以及三个归档页、使用Ant Design中的icon |
| 7        | 2022/03/23 | 博客上线                                                     |
| 8        | 2022/03/30 | 增加了个人简介、顶部、代码高亮                               |



## TodoList

- [x] 静态页面
- [x] Github issus作文章数据源
- [x] react-markdown渲染md
- [x] 翻页功能
- [x] 首页卡片
- [x] 增加代码高亮
- [ ] Demo页面
- [ ] 评论功能
- [x] Redux管理数据
- [x] react-router v6路由
- [ ] 渲染优化，打包优化 （对于性能优化一块仍然不知道）
- [ ]  整理代码, 增加代码复用率
- [x] 三种分类模式
- [x] 类组件为主转为函数式组件为主
- [ ] 文章内部目录
- [ ] 首屏加载时间长，加载图片时间长
- [x] 个人简介
- [x] 返回顶部



## 解决的问题

1. 利用`react-syntax-highlighter`增加了代码高亮。发现`react-syntax-highlighter`库增加代码高亮时只能对代码块标注了语言类别的代码做高亮。而包括我在内的很多人有时并不喜欢将所有代码块注释类别。因此通过控制台发现`react-markdown`解析的组件中代码的内容放在`<pre><code>xxxxxx<code/></pre>`一类的代码。给这一段添加背景色，使得没有注释代码种类的代码也可以与普通文本区分开。

