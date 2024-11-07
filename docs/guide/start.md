# 快速开始
在开始之前，请确保你的设备安装了 Node.js 包管理器，我们推荐使用[Pnpm](https://pnpm.io/zh/)，这也是我们选择的包管理器。

## 安装
新建一个Npm包，在`.npmrc`文件中添加以下内容：

~~~
@lazuli:registry=https://codeberg.org/api/packages/lazuli/npm/
registry=https://registry.yarnpkg.com
~~~

接着运行以下命令：

=== "Npm"

    ``` bash
    npm install @lazuli/ldk2
    ```

=== "Pnpm"

    ``` bash
    pnpm install @lazuli/ldk2
    ```
=== "Yarn"

    ``` bash
    yarn add @lazuli/ldk2
    ```


你就可以在脚本中使用该开发包了，例如：

~~~ts
// 导入函数
import { randomInterger } from "@lazuli/ldk2"

// 生成0-114514随机整数
randomInterger(114514); 
~~~

## 初始化模组
接着，你可以用`initializeMod`函数来初始化模组并配置一些信息：

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

## 打包
你需要一个支持将依赖递归打包进输出文件的脚本打包器，例如Esbuild进行打包。