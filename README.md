# Computer-Forensics Report
The following is the report that I submitted for our Project 4 of CIS-484, where we were tasked to use our computer forensiscs knowledge to find evidence against a suspect of a crime
# Forensics Report
 After receiving the discarded desktop from Mr. Winkler’s residents following the search warrant, I was tasked with examining the hard drive located within the desktop to find any evidence of Mr. Winkler being involved in drug dealing. I first booted up my desktop and loaded a program we use in scanning hard drives called Autopsy in order to find the answers we are looking for. After running the files through the Autopsy program, we were able to uncover many secrets Mr. Winkler was trying to hide from us. The following document will be a detailed report of the evidence I have found in my investigation of Mr. Winkler’s hard drive.
 I can say without a doubt that Mr. Winkler, or Perry Winkler was in fact the owner of this desktop. During my investigation of the files found within the hard drive I was able to come to this conclusion by various different means. While looking into the C: drive there was one name who kept appearing in every file saved to the hard drive, which was Perry. His user was the only account created on the desktop which would lead most to assume this would belong to him. There was also the mater of his web cookies. Every single cookie traced backed to Mr. Winkler showing without a shadow of a doubt that the computer belonged to him and him alone. 
 After determining that the device did in fact belong to Perry Winkler, I continued my investigation looking for the evidence I was tasked to find. We wanted to know if Mr. Winkler was involved in selling drugs in any way shape or form and after investigating the materials I believe this is the case. Will searching through the hard drives files I happened to search into the “EXIF Metadata” folder located in the analysis results section of our Autopsy program. In this folder there were multiple .jpg files of various animals, something I think was clearly a diversion on Mr. Winkler’s part. After going through all the files there were two images which clearly pointed to involvement in drug trafficking. One file which was named “mike’s desk.jpg” contained a photo of what I assume to be Mike’s desk, containing a large bag of marijuana and a roll of cash wrapped in a rubber band. The exact file path for this image is “C:/Users/Perry/Pictures/mike’s desk.jpg”, which was taken on a Canon PowerShot A60. There was a second image in this same folder that also caused some suspicion. This file was named “100_6317(Small).JPG”. In this image file taken on a KODAK Z650 ZOOM DIGITAL CAMERA, there seems to be a bottle of tomato sauce hidden inside the toilet lid of Perry’s bathroom. This would suggest this is where Perry was stashing either his marijuana or cash. Its file path was “C:/Users/Perry/Documents/100_6317 (Small).JPG”. There was also an image file named “da stuff.jpg” located in Perry’s images that showed the open bag of marijuana. After also reviewing some photos that were left inside of the recycling bin, I was able to find multiple images of firearms that Mr. Winkler was trying to delete of his device. During my investigation there was also a excel document found that was titled “Book2.xlsx”. The contents of the document contain money that is due, who owes the money, and the amounts owed. This is presumably from the drug trafficking. I will attach the screenshots of my findings below in this document. 
#
# mike’s desk.jpg:
 ![image](https://github.com/user-attachments/assets/358ad235-20a1-4d2b-9eb9-fb5cb389c439)
# da stuff.jpg:
 ![image](https://github.com/user-attachments/assets/08798fcf-43ec-4f40-8aec-16f9a84aba08)
# Book2.xlsx:
 ![image](https://github.com/user-attachments/assets/9a1ff629-a535-466e-98b1-2f91797a6eb2)
# Firearms:
  ![image](https://github.com/user-attachments/assets/5c6da6c9-cb9d-4a63-a7bc-f7e9772f5c67)
 ![image](https://github.com/user-attachments/assets/1c219b88-7d9e-465f-a24b-3f4bcc1320ec)
![image](https://github.com/user-attachments/assets/8d876e1b-d815-473e-866f-ad75a55f1453)
#


During the investigation is became clear that the suspect wanted to try and conceal and delete evidence for this case. I know this to be due to the report through Autopsy of the received files. In my investigation I began looking into Perry’s search history and on February 24th he searched for ways to be able to clear files from his device, with one search being “What’s the best way to get rid of all evidence on my computer”. After this search Perry was able to find a program that was supposed to be able to completely get rid of all of his files he wanted deleted but clearly this did not work. He also tried to recycle images trough the recycling bin, which is where I was able to locate the above photos of firearms. Along with these photos was a contact of a woman named Mary Reister who may be a client or accomplice. After finding this evidence I decided to use Registry Explorer to examine if there has been any executables that have been ran. In my search I was able to find two programs that seem to offer secure deletion. The first of these programs was called Eraser.exe and the second was named sdelete.exe. Both programs appeared under the downloads folder within Perry’s user account.
Next, I decided to look into any USB devices that may have contained any potential evidence for this case. While investigating in Autopsy I was able to come across two removable storage devices that have been connected to the device. The first device that was plugged into this computer was a SanDisk Cruiser USB device. The device was last entered into the computer on January 26th, 2016 at 21:48:14 UTC. Within the files of this device, I was able to find the image of “mike’s desk” that was previously attached to this document. The next USB device I was able to locate was called Kingston Prod DT 101 G2 USB. This device was last connected to the computer on February 28th, 2016 at 15:46:06 UTC. While investigating the files on this device I was only able to locate pictures that were labeled car1 and car2. These were the only two USB devices I was able to find and although the later does not point to any criminal activity I believe the first image of mike’s desk certainly does.
Lastly in our investigation we wanted to see if Perry had any previous intentions on going on the run. During my earlier investigation into his internet search history earlier, I was able to find searches for plane tickets offered by southwest airlines. There was also letters found with a man named Rick, that detailed there plan on leaving the country and Perry replying “I cant wait to ditch this place”, safe to say Rick is an accomplice in the drug trafficking. We were also able to find an email that was sent to Perry from Rick with their respective email address, these addresses were “perrywin232k@aol.com” and “rickyboys579@aol.com”. The email we were able to find said the following “I finally made it here. I’m using the hotel lobby computer so this cant be traced back to me. I’ll wire the funds to your western union tomorrow. Get rid of the evidence and get on united flight we talked about. See you soon.”  After further investigation I was able to find an image of a map of South America. We then were able to determine Rick is most likely in Brazil as when we traced the plan file that was sent from Rick, the IP address was 186.210.54.196 which is a Brazilian IP address. Within this letter Rick says to Perry to get on the United flight we talked about but Perrys search history is shown that he was searching Southwest flights instead of united Due to this evidence, I believe Perry was in fact selling drugs but am unable to determine if he was able to meet up with Rick in Brazil like they originally planned.
