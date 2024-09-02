# PyTorch_Model
Developing a predictive model for future purposes (probably thesis-related). (Note: I'll edit this ASAP) 

Tools used: NVIDIA CUDA 12.6 (for machine learning purposes), Visual Studio Code
Package Libraries used: 
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118 (CUDA version 11.8)

Summarization:
1.) Vector - is a quantity with magnitude and direction.
2.) Tensor - matrices of vectors to organize and store data in machine learning. 

Random_image_tensor = (width, height, rgb)
Example = (224, 224, 3) values within the tensor

.dtype = there are different data types in tensor (32bit (default), 16bit (faster processing, less precision), 64bit (more precise, lower processing times used for larger models)
.device = different devices but when calculating tensors, they should be the same. Devices: ("cuda" (for nvidia gpu), "cpu", "tpu")
.requires_grad = if gradients required to be computed/tracked
