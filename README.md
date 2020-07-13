# pewpew_stopper https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pinclipart.com%2Fpindetail%2FhTwiim_no-guns-13smok-pixabay-no-more-school-shootings%2F&psig=AOvVaw3egWd6suyiP0ExJn2-EcY6&ust=1594769891486000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCODi_Puyy-oCFQAAAAAdAAAAABAJ

## End-to-End solution to detecting handguns 
- Data preprocessing and augmentation on RoboFlow
- YoloV4 (PyTorch) is trained on a pistol dataset using Colab (bless you Google and your infinite cash pile) 
- PyTorch --> ONNX 
- Running model with TensorRT on Nvidia Jetson Xavier NX to make use of those nice DLA's (Deep Learning Accelerators, for inference)
