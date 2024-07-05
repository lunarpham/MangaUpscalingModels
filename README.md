# Upscaling models for Japanese grayscale manga
![Upscale Example](https://i.imgur.com/fGCiBfq.jpeg)
![Refill Example](https://i.imgur.com/vOfnipp.png)

## **Training info**
| Model |  Architecture  | Type | Scale | HR Size | GT Size | Batch Size | Iterations | Pretrained Model |
|:-------|:----------:|----:|------:|------:|------:|------:|----:|-----:|
| KurehaMangaSR DAT | [DAT Medium](https://github.com/zhengchen1999/DAT) | OTF | 4x | 400px | 128px | 20 | 110000 | None |
| LiloScale |  [ATD Light](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary)  | OTF | 4x | 512px | 128px | 5 | 160000 | None |
| KurehaMangaSR ATDL | [ATD Light](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary) | OTF | 4x | 400px | 128px | 7 | 33000 | LiloScale |
| KurehaMangaRT | [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) | Paired | 1x | 256px | 32px | 3 | 38000 | None |


## **ChaiNNer Templates**

[Google Drive](https://drive.google.com/drive/u/1/folders/13CUiMxvbFJCd4zXUZh5UoVzaqXhupHZ_)

> [!WARNING]  
> Refilling model can cause noisy effect to screentone since it is still in experimental training.

