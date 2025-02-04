# Image Data
![image](https://github.com/user-attachments/assets/d511f9ea-dd3e-413f-8ac4-21e68adb12a8)
![image](https://github.com/user-attachments/assets/ec7c856e-2025-436a-9d99-23c69fb87373)

# Model Summary

==========================================================================================
Model Summary
==========================================================================================
Layer (type:depth-idx)                   Output Shape              Param #
==========================================================================================
AnimeCNN                                 [1, 2]                    --
├─Conv2d: 1-1                            [1, 32, 64, 64]           896
├─MaxPool2d: 1-2                         [1, 32, 32, 32]           --
├─Conv2d: 1-3                            [1, 64, 32, 32]           18,496
├─MaxPool2d: 1-4                         [1, 64, 16, 16]           --
├─Linear: 1-5                            [1, 128]                  2,097,280
├─Linear: 1-6                            [1, 2]                    258
==========================================================================================
Total params: 2,116,930
Trainable params: 2,116,930
Non-trainable params: 0
Total mult-adds (M): 24.71
==========================================================================================
Input size (MB): 0.05
Forward/backward pass size (MB): 1.57
Params size (MB): 8.47
Estimated Total Size (MB): 10.09
==========================================================================================

# Result
![image](https://github.com/user-attachments/assets/51b9b03b-b9b3-482b-b603-865840d7a19d)


