# tensorflow-text-recognition
Handwritten Text Recognition with TensorFlow
Handwritten Text Recognition (HTR) system implemented with TensorFlow (TF) and trained on the IAM off-line HTR dataset. This Neural Network (NN) model recognizes the text contained in the images of segmented words as shown in the illustration below. As these word-images are smaller than images of complete text-lines, the NN can be kept small and training on the CPU is feasible. 3/4 of the words from the validation-set are correctly recognized and the character error rate is around 10%. I will give some hints how to extend the model in case you need larger input-images (e.g. to recognize text-lines) or want better recognition accuracy.


-Run demo


Go to the model/ directory and unzip the file model.zip (pre-trained on the IAM dataset). Take care that the unzipped files are placed directly into the model/ directory and not some subdirectory created by the unzip-program. Afterwards, go to the src/ directory and run python main.py. The input image and the expected output is shown below.
