# Unsupervised Adversarial Image Reconstruction

Unofficial code for https://openreview.net/forum?id=BJg4Z3RqF7 adapted from the original repo.

### Getting Started
1. Install packages with ```pip install -r requirements```. You may need to install PyTorch separately according to https://pytorch.org/.
2. Download CelebA dataset. Note that the official Google Drive link is typically down due to exceeding its daily usage. Try another source like https://www.kaggle.com/jessicali9530/celeba-dataset. 
3. Navigate to ```UNIR/unir/factory/dataset.py``` and set the value of line 19, ```'filename':``` to the path to CelebA images.
4. Return to source folder and run ```python main.py```.
