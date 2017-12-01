
<!--introduced_in=v0.10.0-->
<!-- type=misc -->

全局变量在所有模块中均可使用。
以下变量表面上好像是全局变量，但实际上不是。它们的作用域只在模块内，详见 [module文档]：

- [`__dirname`]
- [`__filename`]
- [`exports`]
- [`module`]
- [`require()`]

以下的对象是特定于 Node.js 的。
有些[内置对象]是 JavaScript 语言本身的一部分，它们也是全局的。

