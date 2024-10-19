# Steganography


**Overview:** The lab explored steganography techniques by hiding and extracting messages within images using various tools.

**Skills Developed:** Steganography, message hiding in images, extracting hidden data.

**Tools Used:** S-Tools, Steghide.


---


**Lab Details**


Through the dates of 10/27/2022 to 10/28/2022, examiner Jake LaBarre performed a steganography analysis of a photo that was received from Dr. A. Steganography is a method of hiding the existence of a message or other data. This is different than cryptography, which hides the meaning of a message but does not hide the message itself (Stallings, 2023). The examiner will use steganography to hide and reveal a message that was requested by Dr. A using the tool S-Tools to perform the task and provide documentation throughout the request. This analysis will show how to perform the proper steps that were requested by Dr. A using the specific photo and message that were requested.  





Analysis

Part 1:
First, the individual must download the S-Tools zip file. This can be downloaded on most websites and is used for Steganography. Steganography is a method of hiding the existence of a message or other data. This is different than cryptography, which hides the meaning of a message but does not hide the message itself (Stallings, 2023). After downloading the S-Tools zip file. The user must open the specific photo requested by Dr. Abushgra. The individual must save the photo as a bitmap (bmp) photo first. Then open the image in paint first if the user is running a Windows 10 or 11 operating system. 

 
Figure 1: Saving specific picture

![image](https://github.com/user-attachments/assets/b64991f0-7e1d-4b59-a426-72300f8aca41)


After, the user will save the image as a .bmp file and replace the existing file from paint. This will allow the user to open the picture in S-Tools. 

 
Figure 2: Replacing saved image from paint

![image](https://github.com/user-attachments/assets/07733592-5011-4136-bb89-416dc83da662)


After the image is saved again, the user should be able to go to the file where the image is saved. Then click on the image and drag the image over to S- Tools. At this point the user should see the image in the S-Tools window. 
 
Figure 3: Picture in S-Tools Window

![image](https://github.com/user-attachments/assets/f8ae4513-4fcc-4f05-a7a0-cc1753eced66)


Now the picture the individual wants to hide message in is in the S-Tools window. It’s time to create the message to hide. First, the user must open notepad. The message that will be hidden is “I am a cyber security professional that belongs to the pioneers”. This message will be typed into notepad then saved as test.txt as shown below in Figure 4.

 
Figure 4: Hidden message saved as test.txt

![image](https://github.com/user-attachments/assets/f6cb706c-d3a7-4e50-ab72-b1840becfc79)


Once the message is saved, the user will drag it over from the saved folder to the S-Tools window. Once this is done, a window will appear showing at the top titled “Hiding 128 bytes”. The user will enter a passphrase and next will verify the passphrase. In this example, “password” was used as the passphrase. In the last section, the Encryption algorithm must be changed to Triple DES by clicking on the down arrow icon then selecting Triple DES. Before selecting ‘OK’ the users screen should look like the screenshot below in Figure 5. 
 
Figure 5: Example screen of encrypting message

![image](https://github.com/user-attachments/assets/8241c9a6-8988-429e-b6be-9293330fac27)


After the user has selected ‘OK’ a new picture will appear titled “hidden data” on the picture. This will be the picture that has the hidden message within the picture. The user shall right click on the image and save the image where the user will know where to find the picture as well as how to identify the difference between the two besides the passphrase. This is shown in Figure 6 below. After, the user will now have an encrypted message within a photograph. 
 
Figure 6: Saved hidden message 

![image](https://github.com/user-attachments/assets/3f3c3af4-115a-4ee5-a36d-d8894afb55a0)



Part 2:
To reveal the hidden message that was encrypted by the user. First, the user must select the photograph with the hidden message in S-Tools or by dragging the photograph into the S-Tools window. After, the user must right click and select reveal. A window will open that is titled “Revealing from ‘hidden_’” or Revealing from ‘the title of the saved document’. A screenshot of the window is shown below in Figure 7. The user must then enter the exact passphrase that was used before. It will be case sensitive, also meaning that if there were capital letters used before. There will need to be capital letters to reveal the message. It will also need to have the same Encryption Algorithm. For the photo used before, the encryption algorithm was Triple DES so the encryption algorithm needs to be the same to reveal the message. 
 
Figure 7: Revealing message window

![image](https://github.com/user-attachments/assets/ba89ccb8-e67c-47ea-a037-57a5b9003d17)


After selecting ‘OK’, a new window will appear that states “Revealed Archive” with a name and the size of the file. The individual will right click on the file name and select save as. The user will then save the file under a name that is easy to remember and to find in the computer that is being used. If the user doesn’t mind where the file goes to then it will be saved under the S-Tools folder. 

 
Figure 8: Archived message

![image](https://github.com/user-attachments/assets/bdfe7e06-2c65-4ac9-a926-bad938c7e92f)


After the saving the file to the folder of the users choice or keeping the file in S-Tools. When the user opens the file. The hidden message will appear. The user may need to choose how to open the file. It is most easily to open the file with notepad since that’s how the user created the message. In Figure 9 below, the message that was hidden is shown in notepad again after being hidden. 
 
Figure 9: Message revealed

![image](https://github.com/user-attachments/assets/4594433b-b42d-4f06-adcb-9c6cc090fb76)


Next, the user will save the photo with the hidden message by right clicking on the photo and selecting save as then saving the photo as “hidden_” or under a name the user can easily remember. The user will then open the photo in paint and saved as a JPEG file. Once the photo is saved, the user should go back into paint and open the same jpeg photo and save the photo as a bitmap photo. Additionally, it should be saved under something to tell the difference between the two photos. The bitmap photo has been saved under hidden_2. It should be noted that neither JPEG or bitmap photos will appear in paint once they have been opened as shown in Figure 10 below. 

 
Figure 10: Bitmap image opened in paint

![image](https://github.com/user-attachments/assets/55b080d4-668f-4db5-a2dd-41695de5d31a)


After saving the new Bitmap image, the user will need to go back into the file the image was saved. Then drag the image into the S-Tools window, the same window will appear asking the individual for a passphrase and to verify the passphrase with the correct encryption algorithm. If the user does not type in the exact passphrase and encryption algorithm then the user will not have access to the file. In this scenario, the passphrase is password and the encryption algorithm is triple DES. Once this is typed into the box, the photo will appear in a new window as shown in Figure 11.

 
Figure 11: Revealing hidden photo

![image](https://github.com/user-attachments/assets/0c389d3c-e90a-41af-8025-0715e1966c34)


To reveal the text within the photo, the user will right click within the new photo that appeared in the S-Tools window then click the reveal button. The same “Revealed Archive” window will then appear. The user will then right click on the name of the file and click save as. In this scenario, the file has been saved as “Reveal2”. After the file has been saved the user will go into the folder where it has been saved or the S-Tools folder and open the file in notepad. Once the file has been opened in notepad the message that was hidden within the picture will appear. Figure 12 below shows the windows and files along with the message that appeared from the new photo. 

 
Figure 12: Revealing message in hidden photo

![image](https://github.com/user-attachments/assets/f699cfef-6d53-440b-b197-d73808879951)



Conclusion

In conclusion, S-Tools is one of the many tools that can be used for steganography. The tool can be used to hide messages within a picture of the users choice. The tool can also be used to reveal pictures and messages as well. Although, the tool doesn’t work well with .jpeg images and there are other steganography tools that offer this option. It does the basic concepts of encrypting and decrypting messages within a picture that will allow a user to perform steganography when needed. 




 
