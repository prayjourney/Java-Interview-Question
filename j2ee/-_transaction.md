# 什么是事务 - transaction

事务是应用程序中一系列严密的操作，所有操作必须成功完成，否则在每个操作中所做的所有更改都会被撤消。例如，将资金从支票帐户转到储蓄帐户中是一项事务，按步骤如下进行：

检查支票帐户是否有足够的资金来支付此转帐操作。

如果支票帐户中有足够的资金，则将该笔资金记入此帐户的借方。

将这些资金记入储蓄帐户的贷方。

将此次转帐记录到支票帐户日志中。

将此次转帐记录到储蓄帐户日志中。
