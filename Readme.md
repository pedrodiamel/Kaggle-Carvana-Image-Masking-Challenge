# Carvana Image Masking Challenge
Automatically identify the boundaries of the car in an image

![](rec/results.png)

## Result

Framework   | Arq      | Result
------------|----------|------
Caffe       |CN-Alexnet|0.99
Pytorch     |Unet      |0.992
TennsorFlow |Unet      |-
Pytorch     |Unet+CRF: |0.993


https://www.kaggle.com/c/carvana-image-masking-challenge/leaderboard

Place: 496 :(

### Dataset

- [metadata](https://www.kaggle.com/c/carvana-image-masking-challenge/download/metadata.csv.zip)
- [sample_submission](https://www.kaggle.com/c/carvana-image-masking-challenge/download/sample_submission.csv.zip)
- [test](https://www.kaggle.com/c/carvana-image-masking-challenge/download/test.zip)
- [test_hq](https://www.kaggle.com/c/carvana-image-masking-challenge/download/test_hq.zip)
- [train](https://www.kaggle.com/c/carvana-image-masking-challenge/download/train.zip)
- [train_hq](https://www.kaggle.com/c/carvana-image-masking-challenge/download/train_hq.zip)
- [train_masks](https://www.kaggle.com/c/carvana-image-masking-challenge/download/train_masks.csv.zip)

## Net
- [FCN-Alexnet](https://github.com/NVIDIA/DIGITS/tree/master/examples/semantic-segmentation)
- [Dice metric](https://github.com/NVIDIA/DIGITS/tree/master/examples/medical-imaging)

- [Unet](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/)
- CRF 


## Credits

- Pedro Diamel Marrero Fernandez (pdmf@cin.ufpe.br)
- Fidel Alejandro Guerrero Peña
- Tsang Ing Ren

