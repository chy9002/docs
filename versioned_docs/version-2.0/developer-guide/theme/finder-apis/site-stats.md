---
title: 站点统计
description: 站点统计 - SiteStatsFinder
---

## getStats()

```js
siteStatsFinder.getStats()
```

### 描述

获取站点的统计信息。

### 参数

无

### 返回值

[#SiteStatsVo](#sitestatsvo)

### 示例

```html
<ul th:with="stats = ${siteStatsFinder.getStats()}">
  <li th:text="${stats.visit}"></li>
  <li th:text="${stats.post}"></li>
</ul>
```

## 类型定义

### SiteStatsVo

```json title="SiteStatsVo"
{
  "visit": 0,
  "upvote": 0,
  "comment": 0,
  "post": 0,
  "category": 0
}
```
