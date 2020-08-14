# Cheque-validation-system

## Current scenario

Current cheque validation procedure involves a lot of manual labour, and is also a time consuming one. This also gives a chance for human errors and inefficiency throughout the
procedure. Person to person the results might vary while checking the necessary details in a cheque. Had there been a standard method carried out for all the cheque, it would definitely lead to less errors. Also outcomes like cheque bouncing are informed to the account holder after quite a number of days, there is good room for improvement regarding this too. By informing the account holder about the status of transaction as soon as possible would save a lot of time.

## Solution to the problem

The proposed methodology verifies a hand written identity on the cheque by identifying and examining the main features in a cheque. It includes complete feature extraction of the account holder’s signature authentication, Account number extraction, cheque number extraction. The complete feature extraction on the cheque is carried and compared with the collected database, which is the account holder’s source of information, is clarified and recognized. A GUI screen is created to show implemented results based on the selection made on the GUI screen and a message box displays the authentication message. Any validations that are not completely read and correlated are emphasized as invalid and it forwarded to the customer for extra action.

## Procedure
1. First we make a point transform.py (Appendix A) where we get the contours of the cheque.
2. Secondly we scan the file using scanner.py (Appendix B) that gets the file and approximate the cheque into a rectangular cheque with the help of the point transform.py
3. Then we extract the features from the cheque we scanned like Account Number, Amount in words, and Amount in digits and Signature with the help of the code written in feature extraction.py (Appendix C).
4. After this we take this feature that are yet just images and convert it into text form to validate all the information from the bank’s database in image to text.py (Appendix D)
5. The last part of this project helps us to find recognize the signature using the file signature recognition.py (Appendix E)

## Requirements
Hardware - Arduino , DC motors, IR sensor
Software - keras, sklearn, pillow,os,pandas,numpy,mataplotlib, ticker,skiimage,opencv,imutils.

 ## Conclusion
 We concluded that this project can be a way to remove human errors, long time involvement in this process, standing in queues etc. This in a way can bring a lot of improvement in the banking sector. Image processing and ML-AI is the future of every sector. It can improve many fields in the Banking field like the person giving money can be replaced; similarly there can be an AI Chatbot that can answer to most of your queries. Like this many fields can be covered. We learnt a lot from this project. The ways to scan something, how to extract features from an image, how can different libraries be used, how to make a model and train it, how to play with files using pandas, how to use keras for machine learning, different activation functions etc.
