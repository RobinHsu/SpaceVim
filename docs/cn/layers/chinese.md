---
title: "SpaceVim chinese 模块"
description: "该模块为中文用户提供了中文的 Vim 帮助文档，同时为部分插件提供了中文帮助文档。"
lang: cn
---

# [可用模块](../) >> chinese

<!-- vim-markdown-toc GFM -->

- [模块描述](#模块描述)
- [启用模块](#启用模块)
- [模块配置](#模块配置)

<!-- vim-markdown-toc -->

## 模块描述

该模块为中文用户提供了中文的 Vim 帮助文档，同时为部分插件提供了中文帮助文档。

## 启用模块

中文用户，可以在配置文件里面添加以下配置来启用该模块，以获取中文帮助文档：

```toml
[[layers]]
  name = "chinese"
```

## 模块配置

加载该模块后，默认的帮助文件语言并未被设置为中文，还需要将 SpaceVim 选项
`vim_help_language` 的值设为 `"cn"`。

```toml
[options]
  vim_help_language = "cn"
```
