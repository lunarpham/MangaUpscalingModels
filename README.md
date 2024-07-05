# Upscaling models for Japanese grayscale manga
![Upscale Example](https://i.imgur.com/fGCiBfq.jpeg)
![Refill Example](https://i.imgur.com/vOfnipp.png)

## **Training info**
| Model |  Architecture  | Type | Scale | HR Size | GT Size | Batch Size | Epoch(s) | Iterations | Pretrained Model |
|:-------|:----------:|----:|------:|------:|------:|------:|-------:|----:|-----:|
| KurehaMangaSR DAT | [DAT Medium](https://github.com/zhengchen1999/DAT) | OTF | 4x | 400px | 128px | 20 | Unknown | 110000 | None |
| LiloScale |  [ATD Light](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary)  | OTF | 4x | 512px | 128px | 5 | 11 | 160000 | None |
| KurehaMangaSR ATDL | [ATD Light](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary) | OTF | 4x | 400px | 128px | 7 | 1 | 33000 | LiloScale |
| KurehaMangaRT | [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) | Paired | 1x | 256px | 32px | 3 | Unknown | 38000 | None |
