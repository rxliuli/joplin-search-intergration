# joplin 搜索集成

## 简介

使用搜索时，相关的乔普林笔记也会显示在搜索结果中。

![search result](https://img.rxliuli.com/20210315180552.png)
![note preview](https://img.rxliuli.com/20210315180626.png)

目前支持的搜索引擎包括

- Google
- Bing
- Baidu

## 贡献

如果你希望添加新的搜索引擎支持，可以提出 issue，或者 fork 后修改提 PR（非常简单）

1. 在 manifest.json 添加匹配的搜索引擎的 url
2. 实现 BaseSearchEngineAdapter 接口