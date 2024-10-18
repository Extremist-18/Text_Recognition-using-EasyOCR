**License Plate detection and Recognition**

Steps:
1) Train your model to a custom dataset.for detection, I have used YoloV8 nano and trained it on a custom dataset.
2) After detection part is done, we can predict the text using easyocr or teserract or any other text recognition model. I have used EasyOCR.
3) Load your best_weight.pt file to model and use predict file to recognize text
