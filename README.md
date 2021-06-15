# OSVGAN-Data-2021
## details
OSVGAN-Data-2021是一个国内社交用户的常用表情包数据集，主要包括熊猫头、蘑菇头两种类型的表情包。每个样本去除了图中文字部分和其他干扰部分，整个数据集分为训练集和测试集。训练集包括512个样本，测试集包括70个样本。每个样本包括一张全局的表情包图像，一条包含14个特征的文本标注，每张表情包图像拆分为头型、五官、上半身、下半身、左手和右手6个部分，每个部分图像与全局图像的文件名相对应。测试集中图像同样有6个部分，另外每张图像有一个包含1条与图片对应的文本标注和4条不匹配的文本标注的文本池。
## samples
#### mushroom head
![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/453_global.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/026_global.jpg)   
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;global&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;global  
![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/453_head.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/453_face.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/453_upbody.jpg)&emsp;&emsp;![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/026_head.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/026_face.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/026_upbody.jpg)  
&emsp;&emsp;&emsp;&emsp;head&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;face&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;upbody&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;head&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;face&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;upbody  
![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/453_downbody.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/453_lefthand.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/453_righthand.jpg)&emsp;&emsp;![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/026_downbody.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/026_lefthand.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/026_righthand.jpg)  
&emsp;&emsp;&emsp;lower body&emsp;&emsp;&emsp;&emsp;left hand&emsp;&emsp;&emsp;right hand&emsp;&emsp;&emsp;&emsp;&emsp;lower body&emsp;&emsp;&emsp;&emsp;&emsp;left hand&emsp;&emsp;&emsp;&emsp;right hand     
#### panda 
![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/110_global.jpg)&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/319_global.jpg)  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;global&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;global  
![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/110_head.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/110_face.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/110_upbody.jpg)&emsp;&emsp;![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/319_head.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/319_face.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/319_upbody.jpg)  
&emsp;&emsp;&emsp;&emsp;head&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;face&emsp;&emsp;&emsp;&emsp;&emsp;upbody&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;head&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;face&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;upbody  
![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/110_downbody.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/110_lefthand.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/110_righthand.jpg)&emsp;&emsp;![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/319_downbody.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/319_lefthand.jpg)  ![Image text](https://github.com/flyingsheepbin/OSVGAN/blob/main/images/319_righthand.jpg)  
&emsp;&emsp;&emsp;lower body&emsp;&emsp;&emsp;&emsp;left hand&emsp;&emsp;&emsp;right hand&emsp;&emsp;&emsp;&emsp;lower body&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;left hand&emsp;&emsp;&emsp;&emsp;right hand        
## dataset for training
[OSVGAN-Data-2021](https://github.com/flyingsheepbin/OSVGAN/blob/main/MemeData-2021.rar)
## dataset for testing
[OSVGAN-Data-2021-eval](https://github.com/flyingsheepbin/OSVGAN/blob/main/MemeGAN-2021-eval.rar)
## contact
please contact lixiaorui@mail.ynu.edu.cn if you have any question.
