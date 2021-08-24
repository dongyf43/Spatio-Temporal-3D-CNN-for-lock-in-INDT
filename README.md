# Spatio-Temporal-3D-CNN-for-lock-in-INDT
Testing model and dataset for article "Y. Dong, C. Xia, J. Yang, Y. Cao, Y. Cao and X. Li, "Spatio-temporal 3D Residual Networks for Simultaneous Detection and Depth Estimation of CFRP Subsurface Defects in Lock-in Thermography," in IEEE Transactions on Industrial Informatics, doi: 10.1109/TII.2021.3103019.".

This code runs with open-source platform Caffe by Yangqing Jia, etc. https://github.com/BVLC/caffe

Dataset for training and testing can be downloaded from one of following two links:

Google Drive: https://drive.google.com/file/d/15qWtj9L3FsjAX0pPB4RS90LWAyWctfhw/view?usp=sharing.

Baidu Cloud: https://pan.baidu.com/s/1oKm2WWBgyySLPderfa-Vcw with extract code: 2k93

This dataset contains 12 infared sequences for 1 training CFRP sample, 12 infrared sequences for 3 testing CFRP samples and corresponding defect detection and depth estimation labels. Infrared sequences are stored with uint16 gray images format, and labels are stored with .mat format by MATLAB.

If you have any question, please contact dongyf@zju.edu.cn, and if you find this code helpful, please consider to cite our work:

@ARTICLE{9511085,

  author={Dong, Yafei and Xia, Chenjie and Yang, Jiangxin and Cao, Yanlong and Cao, Yanpeng and Li, Xin},
  
  journal={IEEE Transactions on Industrial Informatics}, 
  
  title={Spatio-temporal 3D Residual Networks for Simultaneous Detection and Depth Estimation of CFRP Subsurface Defects in Lock-in Thermography}, 
  
  year={2021},
  
  volume={},
  
  number={},
  
  pages={1-1},
  
  doi={10.1109/TII.2021.3103019}}
