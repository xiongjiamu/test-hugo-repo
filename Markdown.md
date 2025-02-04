
Markdown 是一种轻量级的标记语言，用于格式化文档，深受开发者的喜爱，在开源项目中广泛用于编写 README 文件、问题评论、合并请求描述等。本文档将向你介绍 Markdown 的一些常用语法和技巧。

### 1. 标题

使用 `#` 符号来创建标题，标题的级别由 `#` 的数量决定，最多支持三级标题。

```markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
```

### 2. 文本格式

#### 粗体和斜体

使用 `**` 或 `__` 包围文本以创建粗体，使用 `*` 或 `_` 包围文本以创建斜体。

```markdown
**这是粗体**，*这是斜体*
```

#### 引用

使用 `>` 符号创建引用块。

```markdown
> 这是引用的文本。
```

#### 行内代码

使用 \` 来包围文本以创建行内代码。

```markdown
这是一段包含 `行内代码` 的文本。
```

### 3. 列表

#### 无序列表

使用 `-`、`*` 或 `+` 创建无序列表。

```markdown
- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2
* 项目 3
```

#### 有序列表

使用数字和点号创建有序列表。

```markdown
1. 项目 1
2. 项目 2
   1. 子项目 2.1
   2. 子项目 2.2
3. 项目 3
```

#### 嵌套列表

可以嵌套无序和有序列表。

### 4. 链接

#### 内部链接

可以使用 `[链接文本](链接URL)` 创建链接。

```markdown
[GitCode](https://gitcode.com/)
```

#### 外部链接

在文本中输入完整的 URL 或邮箱地址即可自动链接。

### 5. 图片

使用 `![替代文本](图片URL)` 插入图片。

```markdown
![GitCode Logo](https://gitcode.com/assets/gitcode-logo-bf8686e9.png)
```

### 6. 代码块

使用三个 \` 符号创建代码块，可以指定编程语言来进行语法高亮。

\```python
def hello_world():
    print("Hello, World!")
\```

### 7. 表格

使用 `|` 和 `-` 来创建表格，可以指定表格的对齐方式。

```markdown
| 列 1   | 列 2   |
|-------|-------|
| 内容 1 | 内容 2 |
```

### 8. 任务列表

使用 `- [ ]` 或 `- [x]` 来创建任务列表。

```markdown
- [ ] 未完成任务
- [x] 已完成任务
```

### 9. 水平线

使用三个或更多的 `-`、`*` 或 `_` 来创建水平线。

```markdown
---
```

### 10. 引用其他用户或问题

在文本中使用 `@` 符号，可以引用其他用户或问题，他们将会收到通知。

```markdown
@username 提到了你。
```

### 11. Emoji 表情

支持在文本中使用 Emoji 表情，例如 `:smile:` 会显示为 😄。

### 12. 数学公式

使用两个美元符号 `$$` 包围数学公式，可以呈现数学公式。

```markdown
$$
E = mc^2
$$
```

以上是一些常用的Markdown语法和技巧，熟练掌握它们可以帮助你创建更富有表现力、清晰易读的文档和评论。根据你的需求，灵活运用这些语法来提升文档的质量和可理解性。