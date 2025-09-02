---
title: Markdown特色
published: 2025-09-01
updated: 2025-09-02
description: '...'
image: ''
tags: [示例]
category: '示例'
draft: true
pinned: false
---

## Github仓库卡片

::github{repo="Stoeaves/StpCloud"}

创建一个仓库卡片请用： `::github{repo="<owner>/<repo>"}`.

```markdown
::github{repo="Stoeaves/StpCloud"}
```

## 提示

支持提示的类型有: `note` `tip` `important` `warning` `caution`

:::note
Something...
:::

:::tip
Something...
:::

:::important
Something...
:::

:::warning
Something...
:::

:::caution
Something...
:::

### 代码示例：

```markdown
:::note
Something...
:::

:::tip
Something...
:::
```

### 自定义标题

提示标题可以自定义！

:::note[我的自定义标题]
Something...
:::

```markdown
:::note[我的自定义标题]
Something...
:::
```

### 另一种写法

> [!TIP]
> Something...

```
> [!NOTE]
> Something...

> [!TIP]
> Something...
```

### 文字遮挡器

你可以为你的文字添加一个遮挡器，使其看起来像是被隐藏的。

此内容:spoiler[已被**隐藏**]

```markdown
此内容:spoiler[已被**隐藏**]
```