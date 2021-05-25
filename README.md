# Template Matching with OpenCV

OCR Engines like Tesseract library are unable to correctly identify the digits (this is likely due to Tesseract not being trained on credit card fonts). Therefore, we need to devise our own custom solution to OCR credit cards using OpenCV template matching

## Results:

We are able to predict the credit card numbers with OCR A font with 100% accuracy.

![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

## Challenges:

Though we are able to predict digits in OCR A font, there are few credit cards with normal font. Template Matching algorithm is not able to predict digits with normal font accurately as it has been trained only on OCR A font. 
Hence we need to devise an algorithm that can handle both OCR A font and Normal font.

![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)


