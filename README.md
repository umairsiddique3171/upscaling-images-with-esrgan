# upscaling_images_with_esrgan

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
| Low-Resolution Image | High-Resolution Result |
|:--------------------:|:----------------------:|
| ![img3](https://github.com/umairsiddique3171/upscaling_images_with_esrgan/assets/148565997/dd9477cb-aba5-47a0-84f0-bf62d088a0de) | ![img3_rlt](https://github.com/umairsiddique3171/upscaling_images_with_esrgan/assets/148565997/aea061c5-12a8-4de7-9ab9-8d20a286f803)|

| Low-Resolution Image | High-Resolution Result |
|:--------------------:|:----------------------:|
| ![img1](https://github.com/umairsiddique3171/upscaling_images_with_esrgan/assets/148565997/52a6370e-e9b8-4b36-8ad4-f970f3c0d043) | ![img1_rlt](https://github.com/umairsiddique3171/upscaling_images_with_esrgan/assets/148565997/92962e03-386f-448a-88e0-640526d90f90)|

## Acknowledgements
- [xinntao](https://github.com/xinntao/ESRGAN)

## License 
This project is licensed under the [MIT License](https://github.com/umairsiddique3171/upscaling_images_with_esrgan/blob/main/LICENSE).

## Author
[@umairsiddique3171](https://github.com/umairsiddique3171)
