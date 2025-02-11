# Flutter for Web Rendering versions issue

## Introduction
It's appeared that flutter has memory leaks issue with the latest and previous versions deployed on web

Chrome version: Version 132.0.6834.160 (Official Build) (arm64)
Safari version: Version 18.2 (20620.1.16.11.8)
ipad Air M1 Ipad OS 18.2.1 

## command to compile web server
flutter build web

## Flutter 3.27.3 (default rendering)
summery:
Mac Chrome: 64Mb
Mac Safari: 820Mb
Safari iPad: 387Mb
## Image 1: Basic Counter App on Mac Chrome  
![Mac Chrome Counter App](./images/image_3_27_3_chrome_pc.png)

## Image 2: Basic Counter App on Mac Safari  
![Mac Safari Counter App](./images/image_3_27_3_safari_pc.png)

## Image 3: Basic Counter App on Safari iPad  
![Safari iPad Counter App](./images/image_3_27_3_safari_ipad.png)

## Flutter 3.24.0 (default rendering)
summery:
Mac Chrome: 22Mb
Mac Safari: 807Mb
Safari iPad: 389Mb  
summery canvaskit:
Mac chrome: 22Mb
Mac Safari: 664Mb
Ipad Safari: 423Mb
## Image 1: Basic Counter App on Mac Chrome  
![Mac Chrome Counter App](./images/image_3_24_0_chrome_pc.png)

## Image 2: Basic Counter App on Mac Safari  
![Mac Safari Counter App](./images/image_3_24_0_safari_pc.png)

## Image 3: Basic Counter App on Safari iPad  
![Safari iPad Counter App](./images/image_3_24_0_safari_ipad.png)

## Flutter 3.22.2 (default rendering)
summery:
Mac Chrome: 18Mb
Mac Safari: 400Mb
Safari iPad: 68Mb  

summery canvaskit:
Mac chrome: 32Mb
Mac Safari: 400Mb
Ipad Safari: 411Mb
## Image 1: Basic Counter App on Mac Chrome  
![Mac Chrome Counter App](./images/image_3_22_2_chrome_pc.png)

## Image 2: Basic Counter App on Mac Safari  
![Mac Safari Counter App](./images/image_3_22_2_safari_pc.png)

## Image 3: Basic Counter App on Safari iPad  
![Safari iPad Counter App](./images/image_3_22_2_safari_ipad.png)


## Flutter 3.19.6 (default rendering)
summery:
Mac Chrome: 21Mb
Mac Safari: 1.05Gb
Safari iPad: 431Mb
## Image 1: Basic Counter App on Mac Chrome  
![Mac Chrome Counter App](./images/image_3_19_6_chrome_pc.png)

## Image 2: Basic Counter App on Mac Safari  
![Mac Safari Counter App](./images/image_3_19_6_safari_pc.png)

## Image 3: Basic Counter App on Safari iPad  
![Safari iPad Counter App](./images/image_3_19_6_safari_ipad.png)

## Flutter 3.16.2
summery html:
Mac Chrome: 18Mb
Mac Safari: 65Mb
Safari iPad: 140Mb  
## Image 1: Basic Counter App on Mac Chrome  
![Mac Chrome Counter App](./images/image_3_16_2_chrome_pc.png)

## Image 2: Basic Counter App on Mac Safari  
![Mac Safari Counter App](./images/image_3_19_2_safari_pc.png)

## Image 3: Basic Counter App on Safari iPad  
![Safari iPad Counter App](./images/image_3_16_2_safari_ipad.png)


summery canvaskit:
Mac chrome: 18Mb
Mac Safari: 73Mb
Ipad Safari: 104Mb
## Image 1: Basic Counter App on Mac Chrome  
![Mac Chrome Counter App](.images/image_3_16_2_chrome_pc_canvaskit.png)

## Image 2: Basic Counter App on Mac Safari  
![Mac Safari Counter App](.images/image_3_16_2_safari_pc_canvaskit.png)

## Image 3: Basic Counter App on Safari iPad  
![Safari iPad Counter App](./images/image_3_22_2_safari_ipad.png)


## Flutter 3.16.2
summery canvaskit:  
Mac Chrome: 39Mb  
Mac Safari: 400Mb - 1.18Gb (different session return different results)  
Safari iPad: 627Mb - 1.47Gb  
## Image 1: DI1 App on Mac Chrome  
![Mac Chrome DI1 canvaskit App](./images/image_3_16_2_DI1_chrome_pc_canvaskit.png)

## Image 2: DI1 App on Mac Safari  
![Mac Safari DI1 canvaskit App](./images/image_3_16_2_DI1_safari_pc_canvaskit.png)

## Image 3: DI1 App on Safari iPad  
![Safari iPad DI1 canvaskit App](./images/image_3_16_2_DI1_safari_Ipad_canvaskit.png)

## Flutter 3.16.2
summery html:  
Mac Chrome: 37Mb - 50Mb  
Mac Safari: 94Mb - 1.78Gb(same page after reloading 796Mb)  
Safari iPad: 350Mb(complete scan, page refresh didn't change the size) - 1.39Gb  

## Image 1: DI1 App on Mac Chrome  
![Mac Chrome Counter App](.images/image_3_16_2_DI1_chrome_pc_html.png)

## Image 2: DI1 App on Mac Safari  
![Mac Safari DI1 html App](./images/image_3_16_2_DI1_safari_pc_html.png)

## Image 3: DI1 App on Safari iPad  
![Safari iPad DI1 html App](./images/image_3_16_2_DI1_safari_ipad_html.png)