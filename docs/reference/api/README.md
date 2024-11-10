**@lazuli/api v2.2.0** • [**Docs**](globals.md)

***

# LDK: Lazuli API
Add some useful instances for Minecraft Bedrock Edition.

Minecraft 基岩版脚本API的一些实用实例。

## Usage
Add the following code in the `.npmrc` file:

在`.npmrc`文件中添加以下内容：

~~~
@lazuli:registry=https://codeberg.org/api/packages/lazuli/npm/
@minecraft:registry=https://registry.yarnpkg.com
~~~

Then run the following command:

接着运行以下命令：

~~~
npm install @lazuli/api
~~~

## Pack
You need a bundler that supports inline dependencies into the output file *(such as esbuild)* for packaging.

你需要一个支持将依赖递归打包进输出文件的脚本打包器，例如Esbuild。
