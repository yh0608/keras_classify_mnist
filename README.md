# keras_classify_mnist
This is the first try to use keras to train a CNN network, also to test wether the gpu-backend keras is working.

一直在用实验室的caffe做深度学习，为了尝试keras做了这个实验，同时因为我的windows 10系统刚从家庭版升级为专业版，测试原来装的英伟达显卡驱动、cudnn、cudn还能不能正常工作。

## 用keras分类mnist手写体数字
其中 mnist.npz 为数据集， main.py 是主文件。
1. 将本压缩包下载到本地，解压。
2. 把 main.py 中第 36 行 `path = .....`改为数据集的路径。
3. 运行 main.py 。

>注意：在 python 3.5 中路径 都要写成`path='C:\\Users\\yyy\\Desktop\\keras_try\\mnist.npz'`，
如果只有一个斜杠会报错`SyntaxError: (unicode error) 'unicodeescape' codec can't decode bytes in position 2-3: truncated \UXXXXXXXX escape`
