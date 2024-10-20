---
title: 获取模组信息
type: docs
prev: init-mod
---
LDK的核心脚本中内置了一些函数，用于获取`initializeMod`中配置的模组信息。

## 获取模组名称
`getModName()`可以获取模组名称，例如：

~~~ts
import { getModName } from "@lazuli/ldk2";

getModName();
~~~

## 获取模组ID
`getModId()`可以获取模组ID，例如：

~~~ts
import { getModId } from "@lazuli/ldk2";

getModId();
~~~