Poems_generator_Keras
========
 
- 唐诗，古诗，五言绝句自动生成，基于Keras，LSTM-RNN。       
- 附带训练好的模型文件，可直接上手使用。         
- 功能：藏头诗，随机写诗，给定第一句诗/字进行作诗        
 

环境配置
-------
- python3
- tensorflow
- Keras
- h5py
- Jupyter
- numpy……      

 
食用指南
--------
```
from config import Config
#加载模型（若无训练好的模型，会开始训练）
model = PoetryModel(Config)
print('model loaded')

#藏头诗
sen = model.predict_hide('争云日夏')
print(sen)
```
 
输出结果：    
```
争空谁上尽，云云中林翠。日落危西烟，夏更无长塞。
``
  
