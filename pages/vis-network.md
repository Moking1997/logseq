---
title: vis-network
---

## [vis-network](https://www.ame.cool/core/frontend-tools/)

### option
```js
var options = {
  autoResize: true,
  height: '100%',
  width: '100%'
  locale: 'en',
  locales: locales,
  clickToUse: false,
  configure: {...},    // 详细配置请查看'配置'模块，
  edges: {...},        // 详细配置请查看'边'模块，
  nodes: {...},        // 详细配置请查看'节点'模块，
  groups: {...},       // 详细配置请查看'组'模块，
  layout: {...},       // 详细配置请查看'布局'模块，
  interaction: {...},  // 详细配置请查看'交互'模块，
  manipulation: {...}, // 详细配置请'可视化操作'模块，
  physics: {...},      // 详细配置请查看'物理引擎'模块，
}

network.setOptions(options);

```