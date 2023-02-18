### 一、运行环境
 * python 3.7  <br>
 * torch                1.4.0+cu92  <br>
 * torchvision          0.5.0+cu92  <br>
### 二、训练测试命令
 1. train:  <br>
 ``!python train.py --dataset mtwi384 --dataset_root /content/mtwi_2018_train --batch_size 8 --lr 1e-4``  <br>
 2. test:   <br>
 ``!python test_mtwi.py --trained_model weights/ssd384_mtwi_60000.pth --save_folder test/sample_task2 --visual_threshold 0.18 --mtwi_root /content/mtwi_2018_task2_test``<br>
 # 三、参考
 https://blog.csdn.net/weixin_43687366/article/details/126335939 <br>