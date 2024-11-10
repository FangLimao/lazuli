**@lazuli/core v2.2.0** • [**Docs**](globals.md)

***

# LDK: Core Script
A simple mod toolchain's core script for Minecraft Bedrock Edition.

LDK *（一个简单的Minecraft脚本API开发工具链）* 的核心脚本。

## Usage
Add the following code in the `.npmrc` file:

在`.npmrc`文件中添加以下内容：

~~~
@lazuli:registry=https://codeberg.org/api/packages/lazuli/npm/
~~~

Then run the following command:

接着运行以下命令：

~~~
npm install @lazuli/core
~~~

## Pack
You need a bundler that supports inline dependencies into the output file *(such as esbuild)* for packaging.

你需要一个支持将依赖递归打包进输出文件的脚本打包器，例如Esbuild。
