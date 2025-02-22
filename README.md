## 深度学习训练（lls特供版）
你将会籍此开始学习一项有用的技术，在此教程的引导下发动你的自学能力开始吧
### 1. 什么是深度学习
#### 1.1 内容
B站视频 
[传送门1](https://www.bilibili.com/video/BV1L24y1i7v3/?spm_id_from=333.337.search-card.all.click)
[传送门2](https://www.bilibili.com/video/BV1Fs4y1j7fk/?spm_id_from=333.337.search-card.all.click&vd_source=10ae61cea2c37c2c82b44cbb1f3e928b)  

结合参考书pdf学习，也可自行搜索  
#### 1.2 目标
了解深度学习的内容，深度学习的目标等 (了解即可)

### 2. 深度学习的前置知识和准备

#### 2.1 硬件准备
一台拥有GPU(显卡)，能够访问外网的电脑  

#### 2.2 软件准备
1. **python**  
  深度学习通过构建深度神经网络实现，目前主要采用matlab/C++/Python进行编码，其中Python最为简单易学，所以本教程采用Python作为编程语言。  
   + **python 环境安装**  
   编写python需要安装相应的编程环境，就像java需要jdk, C/C++需要编译器。python版本众多，建议安装不是那么新也没那么旧的版本。同时编写python代码需要引用一些库（也称包或依赖），为了方便管理这些包，建议安装anaconda版本的python
   + **IDE 安装**    
   python 编码通常使用pycharm或者vscode等，就像java使用intelJ idea, c/c++使用 clion或者vs. 这里给出一个配置vscode + anaconda环境的教程  
   [传送门](https://blog.csdn.net/Lamber130/article/details/144590838)  
   + **python 语法**  
   环境配完就可以开始学习python语法， python作为弱类型语言和C/java/C++的语法有一些区别，不过也并不很难，可以一边用python在leetcode上刷几道算法题，边用边学为佳 (注：python语法和javascript极为相似，学完python可以顺带看看javascript)  
   [菜鸟教程传送门](https://www.runoob.com/python/python-tutorial.html)  
   [B站一个简短的新手向语法教程](https://www.bilibili.com/video/BV1RTroYfEhA?spm_id_from=333.788.videopod.episodes&vd_source=10ae61cea2c37c2c82b44cbb1f3e928b&p=22)  
   + **其他**  
   此外，你可能还需要自行了解pip包管理、conda虚拟环境管理和conda包管理等内容。
   + **目标**  
   python学习的基础目标是能够通过vscode+anaconda环境编写并运行程序，解决exc1，此外能够完成conda环境的创建并在conda环境中通过pip和conda安装包，解决exc2.  


2. **pytorch**
   + **理论准备**  
   深度学习首先需要构建一个网络模型，网络模型的结构有很多种，常见的包括CNN(卷积神经网络)、Transformer、RNN(循环神经网络)等，简单入门的建议是先学CNN,再学Transformer,最后了解GAN(生成对抗网络)、Diffusion(扩散模型)，LLM(大语言模型)等概念。  
   实际上，深度学习可以主要用于自然语言处理和图像处理两个方面，这里主要以图像处理角度讲述。  
   [CNN传送门](https://www.zhihu.com/people/followbobo/posts?page=3)  
   [Vision Transformer传送门](https://zhuanlan.zhihu.com/p/418184940)  
   不求一次性全部理解，但是至少有个概念，边编码边理解


   + **编码实现**  
   Pytorch是帮助我们实现网络模型结构的一种工具，类似的还有TensorFlow/昇腾等 [教程传送门](https://www.runoob.com/pytorch/pytorch-tutorial.html)。  

   + **目标**  
   学习使用Pytorch框架编码实现几种神经网络并完成一些简单的任务，完成exc3-5. (这里可能跨度有些大，需要理解一些概念（dataset、dataloadr, 优化器等）不过可以对着代码慢慢敲，边写边理解)   
   exc3-通过Resnet18实现CIFAR10数据分类: [传送门](https://www.cnblogs.com/Elijah-Z/articles/16627824.html)  
   exc4-通过Transformr实现CIFAR10数据分类: [传送门](https://blog.csdn.net/FriendshipTang/article/details/137832810)  
   exc5(有一些挑战性)-论文复现（见exc5文件夹）
  

3. **git(可选)**  
   教程传送门（https://www.cnblogs.com/anding/p/16987769.html）  
   **目标**  
   学会创建git仓库，提交代码到远程仓库，创建和切换分支，通过git命令下载github上面的代码
   exc6-创建自己的github账户，并将exc3-5中一项的代码提交到github上
   
