# Upscaling models for Japanese grayscale manga
![Example](https://i.imgur.com/yVQviwF.jpeg)
## **Training info**
| Model |  Architecture  | Type | Scale | HR Size | GT Size | Batch Size | Epoch(s) | Iterations | Pretrained Model |
|:-------|:----------:|----:|------:|------:|------:|------:|-------:|----:|-----:|
| Kureha DAT | [DAT Medium](https://github.com/zhengchen1999/DAT) | OTF | 4 | 400px | 128px | 20 | Unknown | 110000 | None |
| LiloScale  |  [ATD Light](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary)  | OTF | 4 | 512px | 128px | 5 | 11 | 160000 | None |
| Kureha ATDL  | [ATD Light](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary) | OTF | 4 | 400px | 128px | 7 | 1 | 33000 | LiloScale |
