# ImageToCartoonProducer_ARITIFICIAL_INTELLIGENCE(CONVERT AN IMAGE TO CARTOON)

This application is for making the image to its cartoon version(i.e it will convert an image to its cartoon), same as below
![image](https://user-images.githubusercontent.com/104202659/182670230-948efaa4-9fff-4f76-9a3d-633085459d25.png)


![image](https://user-images.githubusercontent.com/104202659/182670426-4534a793-eae5-412f-886a-3cb25818b00c.png)



#  UNDERSTANDING BELOW CODE SNIPPETS


First of all read the image from assigned path in the form of an array, and convert the image into RGB using open CV
![image](https://user-images.githubusercontent.com/104202659/182670649-6457bac5-d38f-4d71-b63b-32371ed5e2ae.png)


Now, check whether the specified path is for image or not, it not then exit
![image](https://user-images.githubusercontent.com/104202659/182671097-7d6adf3e-eb62-4cd3-afc1-9cc900c77448.png)


After checking the above condition, now resize the image into the required size for better performance
![image](https://user-images.githubusercontent.com/104202659/182671278-67c4a9cd-37cc-4f79-ba69-fbc9abe47990.png)
![image](https://user-images.githubusercontent.com/104202659/182671426-55e1a0a0-9938-4efa-a313-6adcf89e058f.png)



Now convert the image into gray color
![image](https://user-images.githubusercontent.com/104202659/182671534-f315b6da-56b9-4854-9664-183dd7b68e63.png)
![image](https://user-images.githubusercontent.com/104202659/182671559-9184261f-2102-4b06-a4b2-de4880d45083.png)



Below code if for proper threshold, and the border for the images as shown below
![image](https://user-images.githubusercontent.com/104202659/182671808-5d72e86b-1615-4c3b-ba15-bcb6729c8759.png)
![image](https://user-images.githubusercontent.com/104202659/182671834-b4784924-5cb4-4af9-93c9-c8016076a5b6.png)


Finally our cartoon image is as below
![image](https://user-images.githubusercontent.com/104202659/182672177-c799921e-12e7-4e72-827e-e2ec89cc4b2f.png)
![image](https://user-images.githubusercontent.com/104202659/182672194-79a9a961-3ffb-4db4-ab8c-9ddd21733b0b.png)




After proper configuration , finally our project is ready, now plot the different different images , see below
![image](https://user-images.githubusercontent.com/104202659/182672029-2bfdcfde-be18-4ece-950c-a230743601f4.png)
![image](https://user-images.githubusercontent.com/104202659/182672064-f186648a-1023-41ee-b9bf-159fca272880.png)




