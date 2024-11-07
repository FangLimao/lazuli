# 初始化模组
你可以用`initializeMod`函数来初始化模组并配置一些信息：

~~~ts
function initializeMod(
  id: string,
  name: string,
  metaData?: ModMetaData,
  event?: (arg: WorldInitializeAfterEvent) => void
): void
~~~

例如：

~~~ts
initializeMod("example-mod", "示例模组");
~~~

请注意，在LDK里不调用`initializeMod`函数，大部分功能仍可以正常运行，此时LDK会使用默认的配置信息运行：

~~~ts
/**
 * Metadata of the mod.
 */
let modData: ModBaseData = {
  id: "ldk",
  name: "Lazuli Development Kit",
}; 
~~~

## 模组元信息
由于脚本API暂时无法读取附加包清单文件，模组的元信息需要在初始化函数中的`metaData?: ModMetaData`参数声明：

~~~ts
/**
 * Metadata of the mod.
 */
export interface ModMetaData {
  /**
   * A short description of the mod.
   */
  description?: string | RawMessage;
  /**
   * Author of the mod.
   */
  author?: string;
  /**
   * Contributors of the mod.
   */
  contributors?: string[] | string;
  /**
   *  Path to the mod icon.
   */
  iconPath?: string;
}
~~~

在其中：

- `description`为模组的简短介绍；
- `author`为模组的作者，只能填一个；
- `contributors`为模组贡献者，可以填多个；
- `iconPath`为模组包图标的资源路径。

!!! tip

    模组元数据接口暂时没有用途，但在未来会添加相关功能