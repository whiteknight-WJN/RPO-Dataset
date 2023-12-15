# RPO-Dataset
RAW image-based Real-world Paired Over-exposure (RPO) dataset for 2023 paper ["Raw Image Based Over-Exposure Correction Using Channel-Guidance Strategy"](https://ieeexplore.ieee.org/abstract/document/10239166)

![image](https://github.com/whiteknight-WJN/RPO-Dataset/assets/90306495/fcc73e11-f373-437e-8b7c-8d4e6c28972d)


# Download link
The complete Real-World RAW Image Dataset (~22.32GB) is available via link：https://pan.baidu.com/s/1L6Fog7X6Xd3tD_aRsyVNtg Extraction code：stzm

## Collection Details

- **Objective**: The dataset comprises 2,600 pairs of real over-exposure images across 650 different scenes.
- **Shooting Equipment**: Canon EOS 5D Mark IV.
- **Auxiliary Equipment**: iPad Pro 2020 / iPhone 11 Pro + tripod.
- **Remote Control App**: Camera Connect for remote control of the Canon camera.
- **Target Scenes**: Various static scenes shot in daylight and LED lighting conditions (both indoor and outdoor).
- **Exposure Ratios**: ×3, ×5, ×8, ×10.
- **Short Exposure Images (Normal, GT)**: Captured in each scene using a tripod-mounted camera. The camera was set to automatic mode to find optimal aperture and exposure time settings, then switched to manual mode to lock these settings. Images were taken using a remote mobile app to control the shutter, minimizing lens vibration.
- **Long Exposure Images (Over-exposure, OE)**: Following the capture of short exposure GT images, only the "exposure time" setting was adjusted using the mobile app to simulate real over-exposure caused by incorrect settings. Four predetermined over-exposure ratios were used (×3, ×5, ×8, ×10). It was ensured that the camera was not touched during both long and short exposure captures to prevent any misalignment due to lens vibration.
- **Estimated Collection Duration**: 1 month.
- **Note**: For each of the 650 GT scenes, corresponding over-exposure images were captured, ensuring pixel-level correspondence with the GT images except for the exposure level.

## Test Set Sample Identifiers

JPEG Format: '113.JPG', '115.JPG', '120.JPG', '121.JPG', '127.JPG', '129.JPG', '130.JPG', ... '650.JPG'.

RAW Format: '113.CR2', '115.CR2', '120.CR2', '121.CR2', '127.CR2', '129.CR2', '130.CR2', ... '650.CR2'.

## Dataset Description

**Real Dataset**: 
This dataset is the first specialized collection to systematically study the generality and practicality of over-exposure correction models. It includes 650 scenes with a total of 2,600 multi long-exposure (over-exposure) images in both RAW and sRGB-JPEG formats, each paired with a corresponding short-exposure (normal-exposure) reference image. The dataset encompasses both indoor and outdoor scenes, captured in daylight or under direct illumination to avoid flickering. The use of mirrorless cameras like the Canon EOS 5D Mark IV, equipped with a full-frame CMOS sensor, ensured high-resolution captures and minimized vibrations.


