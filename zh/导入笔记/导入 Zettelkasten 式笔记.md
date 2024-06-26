---
permalink: import/zettelkasten
aliases:
  - Import Zettelkasten notes
---

如果你一直在使用 Zettelkasten 方法来命名和链接笔记，那么你可能需要将链接从 `[[UID]]` 转换为 `[[UID 笔记标题]]`。

举个例子，在别的笔记软件中，你可能有一个名为 `202301011230 笔记标题` 的笔记，并且在该笔记软件中仅使用 UID `[[202301011230]]` 进行链接。但由于 Obsidian 使用笔记的全名来解析内部链接，这样的链接在 Obsidian 中将会失效。

要将仓库中所有的 `[[UID]]` 链接更新为使用笔记的全名，可以使用[[Markdown 格式转换器]]。

1. 打开 **设置**。
2. 在 **核心插件** 下，启用 **Markdown 格式转换器** 并关闭设置窗口。
3. 在应用窗口左侧的功能区中，选择 **打开格式转换器**（一和零的图标）。
4. 启用 **ZK 卡片链接转换**。
5. 选择 **开始转换**。这将转换仓库中的所有笔记。

> [!tip] Zettelkasten 链接美化
> [[Markdown 格式转换器]] 还可以将链接中的 UID 删除、以美化链接。例如，`[[UID]]` 可以转换为 `[[UID 笔记标题|笔记标题]]`。
> 
> 要美化链接，请在格式转换窗口中启用 **美化 ZK 卡片链接**。

你也可以使用[[时间戳笔记生成器]]在 Obsidian 中创建 Zettelkasten 笔记。