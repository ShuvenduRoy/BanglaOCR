# Bangla OCR

For the purpose of optical character recognizer here i have used keras with convolutional neural network. The dataset is an open sourse 84 class imageset by IIT. The classes include regular character with combined character. I tried various approach to handle the classification problem. The accuracy of some importent model i have got is

| Model Description                         | Accuracy          |
| --------------------------                |  :-------------:	| 
| Simple Deep convolutional  neural network | 85% | 
| CNN with dropout                          | 87% |   
| Image Augmentation                        | 88%     |  
| Pretrained VGG16 model                    | 92% | 

This is one sample training picture

![](img/1.png)

# Important Details
This model is trained on fairly small dataset. It had 1600 train image per class. With more image on hand
and with deeper model the accuracy can be improved farther

## Contact
email: shuvendu1roy@gmail.com
