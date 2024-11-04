# Lazuli Devkit

**Lazuli Devkit**是基岩版脚本API的一个简易开发工具包，尚处开发阶段。

本包提供了一些开发中的实用函数与示例，可以加速你的脚本开发！

## 快速开始
### 安装
新建一个Npm包，在`.npmrc`文件中添加以下内容：

~~~
@lazuli:registry=https://codeberg.org/api/packages/lazuli/npm/
registry=https://registry.yarnpkg.com
~~~

接着运行以下命令：

~~~
npm install @lazuli/ldk2
~~~

你就可以在脚本中使用该开发包了，例如：

~~~ts
// 导入函数
import { randomInterger } from "@lazuli/ldk2"

// 生成0-114514随机整数
randomInterger(114514); 
~~~

### 打包
你需要一个支持将依赖递归打包进输出文件的脚本打包器，例如Esbuild进行打包。