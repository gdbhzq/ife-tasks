# ife-tasks
百度前端技术学院任务

###

### 关于此 repo

- 已经删除 `master` 分支，默认分支是 `gh-pages`，**后面说的`主分支`都默认指 `gh-pages` 分支**
- 可以直接通过 http://v2fe.github.io/ife-tasks/ 后面加上相应路径直接查看代码对应的在线效果
- 在 IFE 上提交任务的时候记得填 demo 地址

### 关于文件结构

- 任务相关文件放到 `/stage-##/task-##/` 下，主 html 文件是 `index.html`
- 公共目录包括 `css`、`js`、`img`、`public` 分别存放任务公共引用的 样式表、JavaScript、图片、其他静态文件

### 关于提交代码

- 建议在此 repo 下创建自己 ID 的分支，修改或新增代码先提交到自己的分支，然后创建 pull request 到 `gh-pages` 分支
（除非如果是很小的修改就直接在主分支上提交，不用发 pr 了）
- 提交了 pr 之后不要急着 merge，把 pr 地址发到群里 @ 所有人来 review，如果另外一个人以上都没什么意见了就可以 merge 并提交到 IFE 了
- 注意代码规范，尽量在提交之前使用 `beautify` 插件格式化代码
- 建议在文件首部添加注释：IFE task 地址、author、reviewer 等字段
- 建议 commit message 填写有意义的信息
