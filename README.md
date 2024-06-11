## Using
### 1. Install Anaconda 
Anaconda is the preferred method of installing DeepFaceLab on Linux.
[Just follow the tutorial](https://docs.conda.io/projects/conda/en/latest/user-guide/install).  

### 2. Install System Dependencies 
You will need FFMpeg, Git, and the most recent NVIDIA driver for your system to use this project.

If you are here, then you already have everything...

### 3. Install DeepFaceLab

Just run it in the terminal.

Check latest cudnn and cudatoolkit version for your GPU device.

```bash
 mkvirtualenv deepfacelab -p $(which python3.7)
 git clone --depth 1 https://github.com/nagadit/DeepFaceLab_Linux.git
 cd DeepFaceLab_Linux
 git clone --depth 1 https://github.com/iperov/DeepFaceLab.git
 pip install colorama ffmpeg-python h5py numexpr "numpy<1.24" opencv-python pyqt5 scikit-image scipy "tensorflow[and-cuda]" tf2onnx tqdm
```

## 4. Download Pretrain (optional)
Use script 4.1 from the scripts directory.
 
Or download manually

[CelebA](https://github.com/nagadit/DeepFaceLab_Linux/releases/download/1.0/pretrain_CelebA.zip)

[FFHQ](https://github.com/nagadit/DeepFaceLab_Linux/releases/download/1.0/pretrain_FFHQ.zip)

[Quick96](https://github.com/nagadit/DeepFaceLab_Linux/releases/download/1.0/pretrain_Quick96.zip)

## 5. Navigate to the scripts directory and begin using DeepFaceLab_Linux ᗡ:
Run all scripts with BASH shell
```bash
bash 1_clear_workspace.sh
```
etc
