---
title: 初始化模组
type: docs
prev: docs/core/
next: get-metadata
---
## 简介
你可以用`initializeMod`函数来初始化模组并配置一些信息：

~~~ts
function initializeMod(
  id: string,
  name: string,
  metaData?: ModMetaData,
  event?: (arg: WorldInitializeAfterEvent) => void
): void
~~~

在LDK里不调用`initializeMod`函数，大部分功能仍可以正常运行，此时LDK会使用默认的配置信息运行：

~~~ts
/**
 * Metadata of the mod.
 */
let modData: ModBaseData = {
  id: "ldk",
  name: "Lazuli Development Kit",
};
~~~

## 