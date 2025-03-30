# Hand

# RGBAvatar
The Resource file is availbe 

- In this Research Paper pdf, [`RGBAvatar`](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://arxiv.org/pdf/2503.12886)
- as an github code, [`Repository`](https://github.com/gapszju/RGBAvatar)

## Method : (RGBAvatar)

$\textbf{Reduced Gaussian Blendshapes Avatar}$

Reconstructing photorealistic, animatable head avatars at speeds sufficient for on-the-fly reconstruction.

Unlike previous models use Linear bases to estimate 3DMM (3D Morphable Model) to model gaussian blendshape, $\textit{RGBAvatar}$ maps tracking 3DMM parameters into reduced gaussian blendshape weights with an NLP. 3DMM is a model using briefl parameters to constructes complext 3d structures such as human face or human siluatte. 3DMM analysis countless 3D face data and create the shared bases beased on the differences of all faces data, and eventually express whichever face combining those bases.

### 3DMM Componenets	

#### 1. Shape (Geometry):
- Based on a dataset of various human facial geometries, a set of shape bases is derived.
- The shape parameters determine how much of each basis to include when reconstructing a face.
- Example: size and position of eyes, nose, mouth, etc.
	
#### 2. Texture:
- Surface details like skin tone, eye color, and wrinkles are also represented using basis vectors and corresponding parameters.

#### 3. Expressions (Blendshapes):
- Blendshape bases are included to model facial expressions from a neutral base face.

#### How it works:
##### 1.	A collection of 3D facial scans from different individuals is analyzed using PCA (Principal Component Analysis) or similar techniques.
##### 2.	A common set of basis vectors is extracted.
##### 3.	A new face is then represented as a linear combination of these bases.

### Color and Parrallel
Further this team developed the color initialization estimation and batch-parrallel Gaussian rasterization to achieve State of art.

## Model Code 

### RGB Avatat Parameter

    parser.add_argument("--subject", type=str, default="bala")
    parser.add_argument("--work_name", type=str, default=None)
    parser.add_argument("--config", type=str, default="config/offline.yaml")
    parser.add_argument("--split", type=str, default="train")
    parser.add_argument("--preload", action="store_true")
    parser.add_argument("--log", action="store_true")


# MICA
[`github`](https://github.com/Zielon/MICA)

# Metrical Tracker

[`Github`](https://github.com/Zielon/metrical-tracker)

# INSTA
[`INSTA`](https://zielon.github.io/insta/)
[`github`](https://github.com/Zielon/INSTA)

# FLAME
[`Code`](https://flame.is.tue.mpg.de/index.html)
# Mano

The Resource page is available

- In this website, [`MANO`](https://mano.is.tue.mpg.de/)

## Method


# HOT3D
An egocentric dataset for 3D hand and object tracking, from Meta

- The dataset, [`HOT3D`](https://facebookresearch.github.io/hot3d/)

# Additional Resources
- [`File Permissions`](https://www.bu.edu/tech/support/research/system-usage/using-file-system/file-permissions/)
- []()