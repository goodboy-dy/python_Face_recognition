tree:<br>
├── 人脸识别.py<br>
├── 人脸训练.py<br>
├── 人脸照相.py<br>
├── 相机测试.py<br>
├── README<br>
├── tools<br>
│   ├── haarcascade_eye.xml<br>
│   └── haarcascade_frontalface_default.xml<br>
└── train<br>
<br>
<br>

必备库安装：<br>
1.pip install opencv-python<br>
2.pip install opencv-contrib-python<br>
3.pip install numpy<br>
4.pip install pillow<br><br>
注：如果安装缓慢，可以使用下面的语句使用清华源安装<br>
pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple 包名<br>
<br>
<br>
编辑：<br>
编辑文件'人脸识别.py'第15行'names = ['None', 'user1', 'user2']'<br>
将其中'uesr1'改为id为1的人的名字，'user2'改为id为2的人的名字，以此类推<br>
例如：<br>
names = ['None', 'aaa', 'bbb', 'ccc']<br>
名字都必须为英文，想显示中文请参照此教程<br>
https://blog.csdn.net/hk121/article/details/80612797<br>
<br><br>
使用顺序:<br>
1.运行 '相机测试'测试你的相机<br>
2.运行 '人脸拍照'拍摄人脸，储存在'train'中。注：‘train’目录必须提前建好，‘id’必须为1，2，3等等<br>
3.运行 '人脸训练'，训练你拍下来人脸，成功后会生成'trainer.yml'<br>
4.运行 '人脸识别'，可识别人脸<br>
<br>
<br>
Inspired by 树莓派实验室 link :https://shumeipai.nxez.com/2018/03/09/real-time-face-recognition-an-end-to-end-project-with-raspberry-pi.html
