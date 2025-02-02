# JavaHacker ——更新ing

—— 记录自己学习Java安全的过程,`无技术含量`

在学习Java安全的过程中很迷茫，遂做记录方便复习

**在此感谢前辈们的研究成果，没有他们就没有我如此方便学习Java安全**

---

**注意事项:**

1.文中涉及到的安全文章都会引出处，自行导航过去查阅文章即可

2.为避免重复的复制粘贴,只会提取文章里的一点点内容作为简洁概括和梳理脉络,具体还需要自行详读师傅们的文章

3.如果看不懂了，就自行查阅文章，或继续往下看。回过头来可能就懂了

4.个人能力有限，大多是个人的理解。如出错欢迎提交issue

5.**不是教学贴，只是简单记录自己学习Java安全的过程**，更像是粗略的读书笔记，所以不详细。

6.个人的学习过程在 【我的学习历程.txt】中

---

### Java安全技能树——正在点技能树中

**1.Java开发基础**

- Java SE
- 代码整洁之道
- Java ASM基础
- IDEA使用技巧

**2.Java安全基础**

- 反射机制

-  类加载机制
-  动态代理机制
-  RMI，RMI攻击
-  本地命令执行和反弹shell
-  JNDI
-  JVM基础（JVM结构，垃圾回收机制/器，字节码结构，执行引擎等）

**3.Java反序列化**

- URLDNS链
- CC

  - CC1
  - CC6，CC6-Shiro
  - CC3
  - CC6-Shiro550
  - CC4
  - Commons Beanutils,CB无依赖
  - cc2
  - cc5
  - cc7
- JDK7u21
- 利用zkar初识序列化结构

**4.开源项目学习**

- JSPHorse-master	和 [JSP免杀学习](https://tttang.com/archive/1315/#toc_0x00)
- 冰蝎自定义协议仿写
- JSPKiller
- Gadgetinspector
- 学习JSPFinder源码,并改进为JSPHunter
- 实现java版本的mysql蜜罐:Groundhog

**5.Fastjson**

- Fastjson基础
- Fastjson 1.2.24
- Fastjson 1.2.24以上版本绕过
- Fastjson1.2.62-1.2.68版本反序列化

**6.Spring基础**

- 浅学设计模式（策略,观察者,装饰,工厂,抽象工厂）（安全开发必看）

- 代码整洁之道（安全开发必看）

- Spring基础

**7.内存马基础**

- 内存马基础
- Filter型内存马
- Listener型内存马
- Servlet型内存马
- Valve型内存马

---

### 用到即查

文档：
https://www.runoob.com/java/java-tutorial.html

Java API:
https://www.w3cschool.cn/java/dict

https://docs.oracle.com/javase/8/docs/api/

**参考:**

https://github.com/Drun1baby/JavaSecurityLearning

[GitHub - phith0n/JavaThings: Share Things Related to Java - Java安全漫谈笔记相关内容](https://github.com/phith0n/JavaThings)

[Y4tacker/JavaSec](https://github.com/Y4tacker/JavaSec)

[JavaSec](https://javasec.org/)

[JavaSecurityLearning](https://github.com/Drun1baby/JavaSecurityLearning)

等