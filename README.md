## Deep-Learning-21-Examples

实验环境：  
Ubuntu 16.04  
Python 3.6.6  
TensorFlow-gpu 1.10.0  
cudatoolkit 8.0  
cudnn 7.1.3  

实验准备：  
1.1050Ti Nvidia显卡驱动安装,在系统设置->软件与更新->附加驱动里选择推荐的NVIDIA专有驱动安装，一般都带版本号，比如384.130，这个型号和显卡的性能对应，如果显卡不够好的话，驱动版本比较低，同时后续支持的cuda版本也比较低。可能默认安装tensorflow后需要对cuda进行降级，以匹配你的显卡驱动。安装完驱动，开机才不会让修改grub -e文件，add nomodeset after quite splash, because of Nvidia is not originally supported by linux.  
2.Anaconda安装  
3.TensorFlow安装 [参考安装方法](https://zhuanlan.zhihu.com/p/50449900)  
4.若cuda版本和显卡驱动不一致，cuda版本降级到合适的版本。conda install cudatoolkit==8.0  

实验步骤：  
1.到需要执行的文件夹，右键打开终端  
2.首先激活之前建立的tf_env环境。source activate tf_env  
3.用python指令执行代码。(tf_env) zhoutaoccu@ailab:~/Github_project/Deep-Learning-21-Examples-master/chapter_1$ python convolutional.py  

本工程是《21个项目玩转深度学习———基于TensorFlow的实践详解》的配套代码


写作这本书的初衷是希望提供一个**深度学习实践案例的合集**，让每个人都可以在“动手实验”的过程中，比较轻松地掌握深度学习和TensorFlow的使用技巧，并且能完整地做出一些有意思的项目。**希望大家能在实践的过程中找到乐趣，如果有任何问题，欢迎通过[issues](https://github.com/hzy46/Deep-Learning-21-Examples/issues)提出纠错或改进建议。**

### 快速指引

以下是各章代码详细的运行方法：

1. [MNIST机器学习入门](chapter_1/README.md)
2. [CIFAR-10与ImageNet图像识别](chapter_2/README.md)
3. [打造自己的图像识别模型](chapter_3/README.md)
4. [Deep Dream](chapter_4/README.md)
5. [深度学习中的目标检测](chapter_5/README.md)
6. [人脸检测和人脸识别](chapter_6/README.md)
7. [图像风格迁移](chapter_7/README.md)
8. [GAN与DCGAN入门](chapter_8/README.md)
9. [pix2pix模型与自动上色技术](chapter_9/README.md)
10. [超分辨率：让图像变得更清晰](chapter_10/README.md)
11. [CycleGAN与非配对图像转换](chapter_11/README.md)
12. [RNN基本结构与Char RNN文本生成](chapter_12/README.md)
13. [序列分类问题详解](chapter_13/README.md)
14. [词的向量表示：word2vec与词嵌入](chapter_14/README.md)
15. [在TensorFlow中进行时间序列预测](chapter_15/README.md)
16. [神经网络机器翻译技术](chapter_16/README.md)
17. [看图说话：将图像转换为文字](chapter_17/README.md)
18. [强化学习入门之Q Learning](chapter_18/README.md)
19. [强化学习入门之SARSA算法](chapter_19/README.md)
20. [深度强化学习：Deep Q Learning](chapter_20/README.md)
21. [策略梯度（Policy Gradient）算法](chapter_21/README.md)

本书包含的项目主要有三部分：第1～11章主要介绍CNN相关的项目，其中8~11章为GAN模型和它的几个重要变体；第12～17章主要介绍RNN、LSTM 相关的项目；第18～21章主要介绍强化学习相关的项目。

### 各章data文件夹下载地址

本工程主要包含的是项目的源代码文件，以chapter\_1/ ~ chapter\_21/ 标识。在有的章节中，还会额外需要一些数据集、模型等文件，我们用chapter_<章节名>\_data/来表示。

例如：第四章有chapter\_4/和chapter\_4\_data/两个文件夹，前者是源代码，后者是在运行程序时会用的数据文件。

由于数据文件通常比较大，建议读者在用到时候再进行下载，下载地址为：[https://pan.baidu.com/s/1i7pKvFf](https://pan.baidu.com/s/1i7pKvFf)，提取码：1kmf。


### 其他链接

- 意见反馈邮箱：hzydl21 [at] 163.com
- 我的专栏博客：[AI Insight](https://zhuanlan.zhihu.com/ai-insight)

### 致谢


