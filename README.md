# Fish-Classification-AI By Tensorflow & Gradio
## Overview
Fish Classification AI เป็นโปรแกรมที่ใช้ในการจำแนกพันธุ์ปลาสวยงามด้วยระบบ AI Machine learning &amp; Deep learning ที่จะทำการแยกพันธุ์ปลาได้จากรูปภาพที่ผู้ใช้ป้อนเข้าไป ซึ่งจะมีพันธุ์ปลาสวยงามใน ฐานข้อมูลทั้งหมด 5 สายพันธุ์ คือ ปลาทอง,ปลากัด, ปลาเทวดา,ปลามังกร และ ปลาหางนกยูง โดยใช้พื้นฐานโปรแกรมมาจาก Tensorflow

![alt text](https://github.com/Naphat2543/Fish-Classification-AI/blob/main/img/AIclassification.PNG)

## Dataset
Dataset รูปปลาสวยงาม 5 ชนิดทั้งหมด 415 ภาพ จัดทำโดยผู้จัดทำได้รวบรวมภาพจากเว็บไซต์ต่างๆ โดยได้รวบรวมไว้ในลิ้ง Google drive นี้ สามารถโหลดได้เลยที่ : (https://drive.google.com/drive/folders/1GiSRWO1cQWjI7w8qTO_RozmkeM3XMQk3?usp=sharing)
--->เมื่อทำการโหลด Dataset มาแล้วสามารถสร้างโฟลเดอร์เก็บไว้บน PC ของเราได้ เพราะ โปรแกรมของเราจะเป็นการเรียกใช้ไฟล์ได้จากเครื่องของเราเอง

## Dataset Description
- angle fish : รูปภาพปลาเทวดา 72 ภาพ
- betta_fish : รูปภาพปลากัด 90 ภาพ
- dragon_fish : รูปภาพปลามังกร 68 ภาพ
- gold_fish : รูปภาพปลาทอง 89 ภาพ
- guppy_fish : รูปภาพปลาหางนกยูง 96 ภาพ

##Tool and Library used & Install 

- Jupyter Nootebook
```
pip install jupyter notebook 
```
- Gradio
```
pip install gradio
conda install gradio
```
- TensorFlow
```
pip install tensorflow
conda install tensorflow
```
- Keras
```
! pip install keras
```
## How to use this project
- ทำการ Dowload ไฟล์ repository ของเราไปนี้ไปไว้ในเครื่องของคุณ
- ทำการ Dowload DataSet ได้จากลิ้ง Google Drive ที่เราได้มอบไว้ให้
- ติดตั้ง Tool และ Library เบื้องต้นที่เราใช้  ได้ตามหัวข้อ Tool and Library used & Install 
- ทำการนำไฟล์ Fish_Classification_AI.ipynb ทีท่านได้โหลดไปนำไป import ใน Jupyter Notebook หรือ Tool ที่ท่านใช้ทำงาน phython 
## How to call DataSet File from your pc
![alt text](https://github.com/Naphat2543/Fish-Classification-AI/blob/main/img/Capture.PNG)
- จากภาพด้านบนท่านสามารถนำ path ที่ไฟล์ Dataset ของท่านตั้งอยู่มาใส่ได้ในตัวแปร DATADIR
## References
[Tensorflow image classification](https://www.tensorflow.org/tutorials/images/classification)





