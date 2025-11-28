# --- Deep Learning (PyTorch) ---
# 注意：PyTorch 建议使用单独的命令安装以确保 CUDA 版本匹配，见文末说明
torch==2.5.1
torchvision==0.20.1
torchaudio==2.5.1

# --- Deep Learning (TensorFlow/Keras Tools) ---
keras==3.6.0
tensorboard==2.20.0
# 注意：你的列表中没有显式的 tensorflow 包，只有相关依赖。
# 如果需要 TF，请取消注释下一行：
# tensorflow==2.16.1

# --- Computer Vision ---
opencv-contrib-python==4.11.0.86
mediapipe==0.10.21
pillow==11.1.0

# --- Simulation & Reinforcement Learning ---
carla==0.9.16
gym==0.26.2
agents==1.4.0
pygame==2.2.0

# --- Data Science & Math ---
numpy==1.24.3
pandas==2.3.3
scipy==1.16.0
scikit-learn==1.7.2
matplotlib==3.10.6

# --- Jupyter & Interactive ---
jupyterlab==4.4.7
notebook==7.4.5
ipykernel==6.31.0
ipywidgets==8.1.7

# --- Utilities ---
tqdm==4.67.1
requests==2.32.5
pyyaml==6.0.2
h5py==3.15.1
protobuf==4.25.8
