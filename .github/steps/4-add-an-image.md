## 步骤 4: 添加图片

接下来我们学习如何在 [Markdown 中插入图片]((https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images))，包括使用相对路径、绝对路径、图片尺寸控制，以及基础排版方式。

### 常规 Markdown

在 Markdown 中，可以通过相对路径（仓库内文件）或绝对路径（图片外接）来插入图片。

图片方括号中的说明文字（alt 文本）在图片无法加载时会显示，同时也会被屏幕阅读器读取，用于提升可访问性。

注意：Markdown 本身不支持直接调整图片大小。

### 示例

**使用仓库内相对路径插入图片：**

```md
![Mona the Octocat](myrepo/original.png)
```

**使用外部URL，绝对路径接插入图片：**
```md
![Mona the Octocat](https://octodex.github.com/images/original.png)
```

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png" width="200">

### HTML 写法

在实际使用中，经常需要控制图片大小或排版（比如和文字并排）。这时可以使用 HTML 语法获得更高的灵活性。

* `alt`：图片无法显示时的替代文本
* `src`：图片来源地址
* `width / height`：控制尺寸（像素）
* `align`：控制对齐方式（left / right）

```md id="img_html"
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
```

### :keyboard: 实操环节

目前我们的博客还比较简单，这一步我们来加一点视觉元素，让页面更生动。

1. 在 `start-blog` 分支中，打开 `day-1.md` 文件进行编辑。

1. 在 **Morning Planning（二级标题）** 下方插入一张图片：

   ```md
   ![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
   ```

1. 切换到 **Preview（预览）**，检查效果。

   - 注意：图片尺寸偏大，不太适合当前布局。

1. 将其替换为 HTML 版本，并控制大小与位置：

   ```md
   <img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
   ```

1. 点击右上角 **Commit changes（提交更改）**，并直接提交到 `start-blog` 分支。

1. 提交完成后，Mona 会继续检查你的内容，并准备下一步学习任务。

<details>
<summary>遇到问题? 🤷</summary><br/>

- 请确认当前编辑的文件和分支是否正确
- 请仔细检查你的语法。HTML 图片标签必须以 `img` 开头，并包含 `src` 属性。

</details>
