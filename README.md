# final-proj-reflection-removal
Final Project at Coder School, Image's reflection removal using Patch GAN &amp; perceptual loss

Reference: https://github.com/ceciliavision/perceptual-reflection-removal

Dataset: 1. [from the ref](https://drive.google.com/drive/folders/1NYGL3wQ2pRkwfLMcV2zxXDV8JRSoVxwA)
         2. [kaggle](https://www.kaggle.com/siboooo/singleimagereflectionremovaldataset)
         
All codes are in MAIN notebook, the function to generate synthetic images is in GENERATE-SYNTHETIC notebook
         
Dir:
```
GAN
│   
└───data
│   │
│   └───real_images
│   │    │  
│   │    └─── tranmission (images without reflection)
│   │    │  
│   │    └─── blended (images with reflection)
│   │
│   └───synthetic_images
│        │  
│        └─── transmission (originial images without reflection mask)
│        │  
│        └─── synthetic (synthetic images (transmission layer + reflection mask) created from function)
│        │  
│        └─── mask (reflection mask after running function)
│   
└───logs
    │
    └─── ckpts 
    │    │  
    │    └─── train 
    │
    └─── output
         │  
         └─── train 

```
