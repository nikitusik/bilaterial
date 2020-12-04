# Bilaterial filter

## Task
Given the image of size M×N, implement and apply a CUDA version of 9-point bilateral filter and store the
result to output image. Missing values for edge rows and columns are to be taken from nearest pixels. CUDA
implementation must make use of texture memory.

## Results

Программа написана в google colab. Сами изображения находятся в Bilaterial.ipynb
Видеокарта Tesla T4, 16 гб оперативы

| CPU time, ms | GPU time, ms | Ускорение  CPU/GPU |
| :---:   | :-: | :-: |
| 106258.602 | 79.518 | 1336 |
