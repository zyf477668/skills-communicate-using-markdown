## 步骤 2: 创建列表

Markdown 支持 3 种常见列表类型：

- [无序列表](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 项目符号列表
- [有序列表](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 数字编号列表
- [任务列表](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) - 带复选框的列表

### 无序列表

无序列表用于展示不强调顺序的条目，每一项前面使用 `-`、`*` 或 `+` 即可。

```md
- Item 1
- Item 2
- Item 3
```

* Item 1
* Item 2
* Item 3

### 有序列表

有序列表用于表示有顺序的步骤或流程。只需使用数字编号即可，Markdown 会自动帮你处理排序。

```md
1. Step 1
1. Step 2
1. Step 3
```

1. Step 1
2. Step 2
3. Step 3

### 任务列表

任务列表是在无序列表基础上扩展而来的，用于表示任务进度。

* 使用 `[ ]` 表示未完成任务
* 使用 `[x]` 表示已完成任务

> 注意：中括号内部需要有一个空格（未完成状态）

```md
- [x] This task is complete
- [ ] This task is not complete
```

* [x] This task is complete
* [ ] This task is not complete

> [!TIP]
> 在 Issue 和 Pull Request 中，也可以使用[任务列表语法](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists)来直观展示进度。

### :keyboard: 实操环节: 为晨间计划添加目标

1. 在 `start-blog` 分支中，打开 `day-1.md` 文件进行编辑。

2. 在 **Morning Planning（二级标题）** 下方添加以下任务清单，用于记录当天目标：

```md
- [ ] 查看 [GitHub Blog](https://github.blog/) 获取选题灵感  
- [ ] 学习 [GitHub Pages](https://skills.github.com/#first-day-on-github) 的使用方法  
- [ ] 将我的第一篇博客转换为网页形式  
```

3. 切换到 **Preview（预览）** 标签页，检查 Markdown 是否正确渲染。

4. 点击右上角 **Commit changes（提交更改）**，并直接提交到 `start-blog` 分支。

5. 提交完成后，Mona 会继续为你准备下一步内容。

<details>
<summary>遇到问题? 🤷</summary><br/>

- 确认当前编辑的文件和分支是否正确。
- 请仔细检查语法。对于任务列表，`[ ]` 内部必须包含一个空格。

</details>
