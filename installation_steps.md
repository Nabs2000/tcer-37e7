## Setting up Conda Environment for Linux OS
1. Install Conda (https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)
2. Create Conda environment -> `conda create -n <name> python=3.7`
3. Install PyTorch 1.6.0 and Cuda 10.1 (https://pytorch.org/get-started/previous-versions/)
4. Create `requirements.txt` file and add libraries from README.md (if missing)

## Troubleshooting

1. "No module named _ext" -> Rename DCNv2-pytorch-*/ to DCNv2/ and run `sh */DCNv2/make.sh`
2. "No module named imageio" -> `pip install imageio`
3. "No module named cv2" ->  `pip install opencv-python`
4. Done!