## 步骤 3: 添加代码示例

接下来，我们来学习如何使用 [代码块（code blocks）](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-code) 以及如何根据不同编程语言实现[语法高亮](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)。

> [!TIP]
> Markdown 支持多种编程语言的语法高亮效果，你也可以尝试其他语言类型看看显示效果。

### 示例：终端命令

````md
```bash
git clone https://github.com/skills/communicate-using-markdown
```
````

```bash
git clone https://github.com/skills/communicate-using-markdown
```

### 示例: Javascript 代码

````md
```js
var myVar = "Hello, world!";
```
````

```js
var myVar = "Hello, world!";
```

### :keyboard: 实操环节

1. 切换到 `start-blog` 分支，并打开 `day-1.md` 文件进行编辑。

1. 在二级标题 **Review** 下方，添加以下内容，用来记录你刚从 GitHub Blog 学到的一段实用代码。

   ````md
   使用 [ffmpeg](https://www.ffmpeg.org) 将图片或视频从深色模式转换为浅色模式

   ```bash
   ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
   ```
   ````

3. 点击 **Preview（预览）** 标签页，检查 Markdown 的显示效果是否正确。

4. 在页面右上角点击 **Commit changes（提交更改）**，并直接提交到 `start-blog` 分支。

5. 提交完成后，Mona 会开始检查你的内容，并为下一步课程做好准备。

<details>
<summary>遇到问题？🤷</summary><br/>

* 确认当前编辑的文件和分支是否正确。
* 注意代码块语法：使用的是三个反引号 ` ``` `，而不是三个单引号 `'''`

</details>
