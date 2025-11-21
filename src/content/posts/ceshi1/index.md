---
title: 测试文章1
published: 2025-10-29
description: "这是测试文章"

author: "Alhena"

pinned: false
draft: false

tags: [测试标签1]
category: 测试分类1

---

<!-- 注释：

title：文章标题（必须）
published：发布日期，格式为YYYY-MM-DD
description：文章描述（必须）
image：封面图。删掉这一行就没有封面图
author: 作者

pinned：是否置顶
draft：是否为草稿

tags：文章标签数组
category：文章分类

 -->

## GitHub Repository Cards

You can add dynamic cards that link to GitHub repositories, on page load, the repository information is pulled from the GitHub API. 

::github{repo="Spr-Aachen/Twilight"}

Create a GitHub repository card with the code `::github{repo="Spr-Aachen/Twilight"}`.

```markdown
::github{repo="Spr-Aachen/Twilight"}
```


## Admonitions

Following types of admonitions are supported: `note` `tip` `important` `warning` `caution`

:::note
Highlights information that users should take into account, even when skimming.
:::

:::tip
Optional information to help a user be more successful.
:::

:::important
Crucial information necessary for users to succeed.
:::

:::warning
Critical content demanding immediate user attention due to potential risks.
:::

:::caution
Negative potential consequences of an action.
:::

### Basic Syntax

```markdown
:::note
Highlights information that users should take into account, even when skimming.
:::

:::tip
Optional information to help a user be more successful.
:::
```

### Custom Titles

The title of the admonition can be customized.

:::note[MY CUSTOM TITLE]
This is a note with a custom title.
:::

```markdown
:::note[MY CUSTOM TITLE]
This is a note with a custom title.
:::
```

### GitHub Syntax

> [!TIP]
> [The GitHub syntax](https://github.com/orgs/community/discussions/16925) is also supported.

```
> [!NOTE]
> The GitHub syntax is also supported.

> [!TIP]
> The GitHub syntax is also supported.
```

### Spoiler

You can add spoilers to your text. The text also supports **Markdown** syntax.

The content :spoiler[is hidden **ayyy**]!

```markdown
The content :spoiler[is hidden **ayyy**]!


