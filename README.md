# 计算机系统要素，从零开始构建现代计算机（nand2tetris）
课程官网：https://www.nand2tetris.org//

相关评论：https://book.douban.com/review/7115224/

搬运的课程【中字】：https://www.bilibili.com/video/av80737268

Coursera课程：https://www.coursera.org/learn/build-a-computer/home/welcome

CSDN关于实现的具体介绍：https://blog.csdn.net/qq_41634283/article/details/103991353

课程论坛：http://nand2tetris-questions-and-answers-forum.32033.n3.nabble.com/
## 课程简介
本书通过展现简单但功能强大的计算机系统之构建过程，为读者呈现了一幅完整、严格的计算机应用科学大图景。本书作者认为，理解计算机工作原理的最好方法就是亲自动手，从零开始构建计算机系统。 通过12个章节和项目来引领读者从头开始，本书逐步地构建一个基本的硬件平台和现代软件阶层体系。在这个过程中，读者能够获得关于硬件体系结构、操作系统、编程语言、编译器、数据结构、算法以及软件工程的详实知识。通过这种逐步构造的方法，本书揭示了计算机科学知识中的重要成分，并展示其它课程中所介绍的理论和应用技术如何融入这幅全局大图景当中去。
全书基于“先抽象再实现”的阐述模式，每一章都介绍一个关键的硬件或软件抽象，一种实现方式以及一个实际的项目。完成这些项目所必要的计算机科学知识在本书中都有涵盖，只要求读者具备程序设计经验。本书配套的支持网站提供了书中描述的用于构建所有硬件和软件系统所必需的工具和资料，以及用于12个项目的200个测试程序。
全书内容广泛、涉猎全面，适合计算机及相关专业本科生、研究生、技术开发人员、教师以及技术爱好者参考和学习
## 章节内容简介
#### 1、布尔逻辑
本章需要实现一下基本逻辑门电路，了解一些数字电路内容即可完成项目。都是基于Nand门（与非门）来实现的，当然在实现其他门电路的时候，可以使用已经实现的门电路。使用其他方式实现也可以<br/>
- and and16 （与门，16位按位与）
- or or16 or8way （或门，16位按位或，8位全或）
- not not16 （非门，16位按位非）
- xor （异或）
- mux mux16 mux4way16 mux8way16 （2选1选择器，16位2选1选择器，16位4选1选择器，16位8选1选择器）
- dmux dmux4way dmux8way （解复用器，解4路复用，解8路复用）

2、布尔运算<br/>
3、时序逻辑<br/>
4、机器语言<br/>
5、计算机体系结构<br/>
6、汇编编译器<br/>
7、虚拟机I：堆栈运算<br/>
8、虚拟机II：程序控制<br/>
9、高级语言<br/>
10、编译器I：语法分析<br/>
11、编译器II：代码生成<br/>
12、操作系统<br/>
13、后续挖掘
