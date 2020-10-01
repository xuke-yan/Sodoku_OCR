# Sodoku_OCR

Inspired by https://www.pyimagesearch.com/2020/08/10/opencv-sudoku-solver-and-ocr/#pyi-pyimagesearch-plus-pricing-modal

result: ![Image of result](https://github.com/xuke-yan/Sodoku_OCR/tree/master/results/result3.jpg)

### Required packages:

  ```$ pip install py-sudoku```
  
  ```$ pip install tensorflow```
 
 Also Install OpenCV 4.0.0 or later
 
### Usage:
  Training: ```$ python train_digit_classifier.py --model output/digit_classifier.h5``` 
  
  Testing: ```$ python solve_sudoku_puzzle.py --model output/digit_classifier.h5 --image sample3.jpg```
