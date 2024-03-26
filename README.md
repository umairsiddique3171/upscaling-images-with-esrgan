# upscaling_images_with_ecrgan

## Introduction

Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN) have gained significant attention in the field of computer vision for their ability to upscale low-resolution images while preserving important details. This project delves into the application of ESRGAN for upscaling images, aiming to generate high-resolution outputs from low-resolution inputs while maintaining the fidelity of the original content.

## Usage

To use this repo to upscale your images, follow these steps:

1. Clone the repository from GitHub:
   ```
   git clone https://github.com/umairsiddique3171/upscaling_images_with_esrgan.git
   cd upscaling_images_with_esrgan
   ```
2. Create a Virtual Environment:
   ```
   python -m virtualenv env
   .\env\Scripts\activate
   ```
3. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Download Pre-trained Model ``RRDB_ESRGAN_x4.pth`` from [here](https://drive.google.com/drive/u/0/folders/17VYV_SoZZesU6mbxz2dMAIccSSlqLecY).
5. Paste the downloaded Model in ``ESRGAN\models``.
6. Paste the low resolution images in ``ESRGAN\LR``.
7. Run ``ESRGAN\test.py`` file:
   ```
   cd ESRGAN
   python test.py
   ```
8. You would be able to access resulted high resolution images from ``ESRGAN\results``.

## Results 


## Acknowledgements

- [xinntao](https://github.com/xinntao/ESRGAN)

## License 
This project is licensed under the [MIT License](https://github.com/umairsiddique3171/upscaling_images_with_esrgan/blob/main/LICENSE).
## Author

[@umairsiddique3171](https://github.com/umairsiddique3171)
