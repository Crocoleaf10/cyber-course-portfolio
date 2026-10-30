# Task 1. Embed a secret message into a image
First i downloaded this shark image of the internet and renamed it "cool shark". 
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/a8e9b3cb-8372-4806-bc71-15f523c8ca5d" />
Then i used the xxd tool to see the image in a binary format.
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/20696269-9fd1-4c58-acea-ab57b8b4e58a" />
Now i created a secret message that i will later imbed into the image.
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/7d379e5e-feea-48fd-91ec-f1e71f4f7f29" />
Then i copied the original image
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/026fd3b1-e472-42b6-82df-13d27affc6e1" />
After that i compared the original image and the copies hash side by side and it showed me that its the same file despite having a different name.
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/13da352a-2967-4b00-a6da-84d042149550" />
Now i used the tool steghide to embed the earlier written message into the original image.
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/43297f59-2e73-4fe2-b24a-97c68f2466e7" />
I then again compared the hashes of the original picture and the copy and there now is a difference in the hashes.
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/534c80aa-c742-4160-95d1-99e4016876be" />
After that i deleted the secret message.
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/877c1f8e-5748-4fac-a9b7-e35aae8d69c9" />
And lastly i extracted the hidden message from the image.
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/82158ebf-5eb7-48e6-9224-4139e832190e" />
# Task 2. Use two methods to extract the message from the two given images(cat1.jpg and cat2.jpg)
Method 1:I used the tool steghide to extract each images to figure out which one hid the message and it was cat1.jpg
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/8a833ed7-c749-4ca0-a086-ad6dad2da21a" />
Method 2:I checked the size of both images and determined that the bigger sized one must have the message and that image was cat1.jpg
# Task 3. Embedding a xlsx file into a audio file
First i searched for royalty free audio of frog sounds
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/34d3e4c2-7b01-46c6-a0f7-78f63c48da33" />
Then i used steghide to embed the xlsx file into the audio file
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/5a466422-15b7-4fac-8bff-10e1c1140c43" />
Now if i want to extract my xlsx file i will use steghide to extract the xlsx file
<img width="960" height="600" alt="image" src="https://github.com/user-attachments/assets/73b48745-3ea4-40c8-a299-88e419cb7ee0" />
