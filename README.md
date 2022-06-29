Java8实战实例代码

===============

该存储库包含《Java 8实际操作：Lambdas、Streams和函数式编程》一书中示例和测验的所有源代码。

所有示例的源代码都可以在src/main/java/lambdasinaction目录中找到

第1章：Java 8：为什么要关心？

第2章：通过行为参数化传递代码

第3章：Lambda表达式

第4章：使用流

第5章：使用流处理数据

第6章：使用流收集数据

第7章：并行数据处理与性能

第8章：重构、测试、调试

第9章：默认方法

第10章：使用Optional作为null的更好替代

第11章：CompletableFuture：可组合异步编程

第12章：新的日期和时间API

第13章：功能性思维

第14章：函数式编程技术

第15章：OOP和FP的混合：比较Java 8和Scala

第16章：结论和Java的“下一步在哪里”

附录A：其他语言更新

附录B：杂项库更新

附录C：在一个流上并行执行多个操作

附录D：Lambdas和JVM字节码我们将在更新本书时更新存储库。敬请期待！

确保安装了JDK8

最新二进制文件可在此处找到：http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html

$java-版本


java版本“1.8.0\u 05”java（TM）SE运行时环境（build 1.8.0\u 05-b13）java HotSpot（TM）64位服务器VM（build 25.5-b02，混合模式）

您可以在此处下载预览版本：https://jdk8.java.net/


编译/运行示例

使用maven：

$mvn编译

$cd目标/类别

$java lambdasinaction/chap1/FilteringApples

或者，您可以在src/main/java目录中手动编译这些文件

您还可以在您喜爱的IDE中导入项目：*在IntelliJ中使用“文件->打开”菜单并导航到项目所在的文件夹*在Eclipse中使用“文件->导入->现有Maven项目”（还可以修改“Reduntant超级接口”以报告为警告而不是错误*在Netbeans中使用“文件->打开项目”菜单
