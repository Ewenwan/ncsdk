# NCSDK back soon  加速深度学习推理的Intel Movidius神经计算棒（NCS）


    软件开发包（很重要）：

    Intel Movidius Neural Compute SDK（NCSDK）
    Neural Compute Application Zoo (NC App Zoo)
    目前，网上可以找到配套NCS使用的软件开发包主要有上面两个，放在Github上，用户很容易获取到，
    NCSDK属于官方提供发布的，很权威，里面包含了软件工具、API以及例程等资料，
    通过对这几个工具以及API的理解可以有效的了解NCS的工作原理；

    NC App Zoo是一个让用户可以分享自己使用NCS做的一些应用、模型的地方.

[购买](http://www.eeboard.com/shop/?c=products&a=view&id=4984)
  
    
    API则是NCS计算神经棒的硬件调用接口，
    通过训练得到的网络模型可以使用mvNCCompile工具编译为能被NCS识别的graph文件，
    通过调用API，NCS可以通过USB接口方便的与主机（Up Squared Board、树莓派3B）通信，
    NCS利用训练好的网络模型计算出图像分析的结果，并传输到主机上，完成推理工作。
    
![](http://www.eeboard.com/wp-content/uploads/2018/01/neuralcompetestick-3-500x326.png)
    
    

The https://github.com/movidius/ncsdk github repository will be temporarily down starting 8/8/2018 and will be revived soon under a less restrictive open source license.

In the meantime latest versions of the software can be downloaded at these links:

**1.12.00.01:**</br>
https://ncs-forum-uploads.s3.amazonaws.com/ncsdk/ncsdk-01_12_00_01-full/ncsdk-1.12.00.01.tar.gz


**2.05.00.02:**</br>
https://ncs-forum-uploads.s3.amazonaws.com/ncsdk/ncsdk-02_05_00_02-full/ncsdk-2.05.00.02.tar.gz


**Documentation will remain here:** </br>
https://movidius.github.io/ncsdk/



We apologize for any inconvenience this may have caused.  
