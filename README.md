* 模块化开发的意义：
* 将一个复杂的程序依据一定的规则(规范)封装成几个块(文件), 并进行组合在一起
* 块的内部数据与实现是私有的, 只是向外部暴露一些接口(方法)与外部其它模块通信
*
* 模块化开发的好处：
* （1）避免变量污染，命名冲突
* （2）提高代码复用率
* （3）提高了可维护性
* （4）方便依赖关系管理
*
* 图中require.js、sea.js的特点
* require.js是依赖前置，sea.js是按需加载，这是设计之初的特点
* 随着规范的优化演变，我的demo中使用的是最新的规范，因此验证的结论是相反的
* 最新规范require.js按需加载，sea.js依赖前置