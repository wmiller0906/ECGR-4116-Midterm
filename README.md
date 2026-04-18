# How To Use
Directions detailed are for a Linux-based OS with a CUDA-capable GPU. Follow the same general steps, but the commands are Linux specific and will need to be adapted for what your OS requires.

### Directions for Linux
1. Clone the repository and change to this directory.
2. Create a virtual environment with Python 3.11. **python3.11 -m venv venv**
3. Activate the venv **source venv/bin/activate**
4. Install dependencies **pip install -r requirements.txt**
5. Torch may fail to install from requirements. If so, run the following to install Torch for CUDA: **pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128**
6. Open _Midterm Project.ipynb_ in the Jupyter application of your choice.
7. Adjust the paths in the third cell to match your directory paths to the training folder, test folder, and the directory where generated images are stored.
8. Run the program

### Other files for grader
Inside the other-files-for-grader directory of this repo are generated files from the completion of this project, such as SRGAN generated images, epoch checkpoints, and final models.
