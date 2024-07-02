# 3D-anatomy-Reconstruction-
### Working with 3D images has been a challenging task because of the issues like image having multiple and incompatible formats, large dimensions and massive size. These all problems make working with 3D images ineffecient even the GPU'S take plenty amount of time in building or reconstructing a 3D image.
### The Deep Learing model we have optimized is medical images completer, the baseline model uses interpolation techniques to reduce all the image into a common dimension followed by using denoising auto-encoders to reconstruct the image.
### We have optimized the accuracy for a given epoch, using concepts from googleNet and resNet architecture, the accuracy to reconstruct the image at about 50 epochs has been increased to double it's previous value on an average for every incomplete test image. 


| Overview       | Details |
| -------------- | ------- |
| **Title**      | 3D Anatomy Reconstruction |
| **Link to paper** | [Paper](https://arxiv.org/abs/2309.04956) |
| **Benchmark**  | Multi-class Anatomy Completor |
| **Link to benchmark dataset** | [Download (multi-class)](https://files.icg.tugraz.at/f/b0623306eb9246be8c3c/?dl=1) |
| **Data structure** | voxel occupancy grid |
| **Pretrained Model** | [Model](https://drive.google.com/drive/folders/15iy86nhCFKLpnIPgxniZjJqspSbZv3Ub?usp=drive_link ) |

## To run the training Code for Unet

1. Navigate to the `Unet` directory:
    ```sh
    cd Unet
    ```
2. Run the `code.ipynb` file.
![Result from UNET where left is incomplete image and right one is complete one](https://github.com/krishmittal1301/3D-anatomy-completer-/blob/main/Unet/WhatsApp%20Image%202024-05-07%20at%2010.55.53_28ebe640.jpg)
**Figure: Result from UNET where the left is the incomplete image and the right one is the complete one.**


## Similarly we can run the code for skip connections and GoogleNet.
![Result from UNET where left is incomplete image and right one is complete one](https://github.com/krishmittal1301/3D-anatomy-completer-/blob/main/Unet%2BSkip/WhatsApp%20Image%202024-05-14%20at%2016.10.08_2b9a161b.jpg)
**Figure: Result from Unet+Skip connections.**
