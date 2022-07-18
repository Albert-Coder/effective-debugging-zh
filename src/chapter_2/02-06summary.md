# 总结

本章通过两个内存管理器的实现例子解释了用户的内存块是如何被管理的。对于调试的目的，我们最关心编码在块标签或者其他堆元数据的（取决于具体实现）内存块状态信息。通过利用这些堆元数据，一些调试器命令被创建出来用于揭露任意一个内存块的状态。正如我们看到，当我们知道一点堆内在，容易获取我们取消的信息。如果读者使用不同的内存管理器，鼓励你自己编写相似的工具。你很快会发现你从它们获取信息是很容易的。有了这些知识和帮助工具，我们准备好挑战困难的内存问题。