# pewpew_stopper

## End-to-End solution to detecting handguns 
- Data preprocessing and augmentation on RoboFlow
- YoloV4 (PyTorch) is trained on a pistol dataset using Colab (bless you Google and your infinite cash pile) 
- PyTorch to ONNX 
- Running solution on Nvidia Jetson Xavier NX with TensorRT to make use of those nice DLA's (Deep LEarning Accelerators, for inference)
