README
===========================
## 《Java编程思想》笔记
* 看了差不多两个月才看完，在这个过程中痛并快乐着，一天只能看十多页，书中有穿插着一些设计模式应用到实际的例子中。这本书不会一味地讲语法，更多的是会讲一些Java的设计思想，比如他不会一开始就教你怎么用泛型，而是先介绍为什么会出现泛型，没有泛型会有什么后果，Java设计者又为什么会选择泛型的擦除，书中对是否选择泛型的擦除等进行了激烈的讨论,经常会与C++做比较，看起来是比较有意思的。
下面有目录，每个章节的包含的内容，可以直接点击超链接进去正文。
## 正文
* 第一部分: https://github.com/mowenlong/Thinking-in-Java/blob/master/src/test/Test1.java
* 第二部分: https://github.com/mowenlong/Thinking-in-Java/blob/master/src/test/Test2.java
* 第三部分: https://github.com/mowenlong/Thinking-in-Java/blob/master/src/test/Test3.java

**里面的笔记记得特别的详细!!!**
**建议clone下来，一个个点进去看**
****
	
|Author|龙|
|---|---
|E-mail|741321320@qq.com
|Website|http://www.mowenlong.com
|CSDN|https://blog.csdn.net/weixin_38104426


****
## 目录

### [第一部分](/src/test/Test1.java)
 * 第一章：对象导论
	 * 访问修饰符
	 * 继承
		 * 伴随多态的可互换对象
		 * 单继承结构
 	* 容器
	* 参数化类型
 	* 对象的创建和生命周期
 	* 异常处理:处理错误
 
 * 第二章：一切都是对象
	 * 用引用操纵对象
	 * 必须由你创建所有对象
		 * 存储到什么地方
		 *  特例：基本类型
		 * 高精度数字
		 * java中的数组
	* 永远不要销毁对象
		* 作用域
		* 对象的作用域
	* 基本成员默认值
	* static关键字:
	* 注释文档的语法
	* java的基本类型数组 和 包装器类型数组
	* 第一个java程序
 * 第三章：操作符
	 * java操作符
	 * 算术操作符
	 * 关系操作符
	 * 逻辑运算符
	 * float 与 double 的区别 
	 * 前缀式与后缀式的区别
	 * 测试对象的等价性
	 * 注意数值过界
 * 第四章：控制流程
	 * 迭代
	 * return,break和continue
	 * switch
 * 第五章：初始化与清理
	 * 构造器
	 * 方法重载
	 * this关键字
	 * 清理:终结处理和垃圾回收
	 * 垃圾回收只与内存有关
	 * finalize()的用途何在?
	 * 终结条件
	 * 垃圾回收器如何工作
	 * 成员初始化
	 * 可变参数列表
	 * 枚举类型
 * 第六章：访问权限控制
	 * 包:库的单元
	 * java解析器的运行过程
	 * 定制工具类
	 * java的访问修饰符
	 * 类的访问权限
 * 第七章：复用类
	 * 复用代码
	 * 组合语法
	 * 继承语法
	 * 初始化基类
	 * 代理
	 * 结合使用组合和继承
	 * 在组合与继承之间选择
	 * 继承
	 * fianl关键字 
	 * 初始化及类的加载
	 * 继承与初始化
 * 第八章：多态
	 * 三大基本特征
	 * 多态的作用
	 * 再论向上转型
	 * 忘记对象的类型
	 * 转机
	 * 可扩展性
	 * 缺陷
	 * 构造器和多态
	 * 继承与清理
	 * 初始化过程
	 * 协变返回类型
	 * 向下转型与运行时类识别
### [第二部分](/src/test/Test2.java)
 * 第九章：接口
	 * 抽象类和抽象方法
	 * 接口
	 * java中的多重继承
	 * 通过继承来扩充接口
	 * 组合接口时的名字冲突
	 * 适配接口
	 * 接口中的域
	 * 嵌套接口
	 * 接口与工厂
 * 第十章：内部类
	 * 创建内部类
	 * 链接到外部类
	 * 使用.this与.new
	 * 嵌套类(静态内部类)
	 * 内部类与向上转型
	 * 在方法和作用域内的内部类
	 * 匿名内部类
	 * 嵌套类
	 * 为什么使用内部类?
	 * 内部类的继承
	 * 局部内部类
 * 第十一章：持有对象
	 * 容器
	 * 基本的容器类型
	 * 容器的基本概念
	 * 与接口打交道
	 * List
	 * 迭代器
	 * LinkedList
	 * 栈(Stack)
	 * Set
	 * Map
	 * Queue
	 * PriorityQueue
	 * Collection和Iterator
	 * Foreach与迭代器
	 * 适配器方法惯用法
	 * 总结
### [第三部分](/src/test/Test3.java)
 * 第十三章：字符串
	 * 不可变的String
	 * 重载 "+" 与StringBuilder 
	 * 无意识的递归
	 * String类基本的API
 * 第十四章：类型信息
	 * Class对象
	 * 类字面常量
	 * 代理
 * 第十五章：泛型
	 * 适合于许多许多的类型
	 * 多态算是一种泛化机制
	 * 简单的泛型
	 * 一个元组类库
	 * 一个堆栈类(Stack)
	 * 泛型接口
	 * 泛型方法
	 * 杠杆利用类型参数推断
	 * 可变参数与泛型方法
	 * 用于Generator的泛型方法
	 * 一个通用的Generator(对象生成器)
	 * 简单元组的使用
	 * 匿名内部类
	 * 擦除的神秘之处
	 * java泛型是使用擦除来实现的
	 * C++的方式
	 * 迁移兼容性
	 * 擦除的核心动机
	 * 擦除的问题
	 * 边界处的动作
	 * 擦除的补偿
	
