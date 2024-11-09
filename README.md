# 113-1-AIOT-hw1

Using device: cuda

===============================

X's shape: torch.Size([759, 8]) | Y's shape: torch.Size([759, 1])
![image](https://github.com/user-attachments/assets/8631e493-65e1-4057-81b2-1b75f130ce36)

![image](https://github.com/user-attachments/assets/3e4c0d9e-9bb3-4dec-99ee-fd1121bbbbe6)


===== 比較不同激活函數 =====

使用激活函數: ReLU
Epoch: 20/100 | Loss: 0.6202
Epoch: 40/100 | Loss: 0.5690
Epoch: 60/100 | Loss: 0.5317
Epoch: 80/100 | Loss: 0.4951
Epoch: 100/100 | Loss: 0.4716

使用激活函數: LeakyReLU
Epoch: 20/100 | Loss: 0.6278
Epoch: 40/100 | Loss: 0.5932
Epoch: 60/100 | Loss: 0.5567
Epoch: 80/100 | Loss: 0.5188
Epoch: 100/100 | Loss: 0.5065

使用激活函數: GELU
Epoch: 20/100 | Loss: 0.5981
Epoch: 40/100 | Loss: 0.5565
Epoch: 60/100 | Loss: 0.5300
Epoch: 80/100 | Loss: 0.5014
Epoch: 100/100 | Loss: 0.4845

使用激活函數: ELU
Epoch: 20/100 | Loss: 0.5780
Epoch: 40/100 | Loss: 0.5456
Epoch: 60/100 | Loss: 0.5201
Epoch: 80/100 | Loss: 0.5023
Epoch: 100/100 | Loss: 0.5107

===== 比較不同優化器 =====

使用優化器: SGD
Epoch: 20/100 | Loss: 0.6366
Epoch: 40/100 | Loss: 0.6113
Epoch: 60/100 | Loss: 0.5893
Epoch: 80/100 | Loss: 0.5566
Epoch: 100/100 | Loss: 0.5381

使用優化器: Adam
Epoch: 20/100 | Loss: 0.7196
Epoch: 40/100 | Loss: 0.6924
Epoch: 60/100 | Loss: 0.6634
Epoch: 80/100 | Loss: 0.6320
Epoch: 100/100 | Loss: 0.6078

使用優化器: RMSprop
Epoch: 20/100 | Loss: 0.4816
Epoch: 40/100 | Loss: 0.4230
Epoch: 60/100 | Loss: 0.3999
Epoch: 80/100 | Loss: 0.3995
Epoch: 100/100 | Loss: 0.3821

使用優化器: Adagrad
Epoch: 20/100 | Loss: 0.6467
Epoch: 40/100 | Loss: 0.6135
Epoch: 60/100 | Loss: 0.6273
Epoch: 80/100 | Loss: 0.6274
Epoch: 100/100 | Loss: 0.6202

![image](https://github.com/user-attachments/assets/8aee3253-051c-44db-9b2b-dcb7a8be3348)
