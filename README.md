# Phishing Amalysis-p3
## Question
<picture>![image](https://github.com/user-attachments/assets/4619bf1d-19bb-4830-93da-c4da0ebc68de)
</picture>

### Using the ‘**eioc.py**’ tool:
  
+ From the snapshot below, the tool is able to extract all the necessary components in the email file. Without opening the file, we know it has an attachment,

<picture>![image](https://github.com/user-attachments/assets/ddac9406-6e04-4ae9-bf4b-c6dfb958a5c9)
</picture>
+ We used the ‘emldump.py’ [tool to analyze MIME file] to read the parts or composition of all that is contained in the email. You can see the email contains 5 parts/indices as seen below, including the attachment as 5.

<picture>![image](https://github.com/user-attachments/assets/f2a1a4ec-6bf5-4972-a3fa-307bc0fe698a)
</picture>

+ We want to analyze the doc file as seen in index 5. Let’s extract the attached doc file using the ‘-s’ argument to select the particular stream interested in and ‘–d’ argument to dump the file.
<picture>![image](https://github.com/user-attachments/assets/6b625881-7659-45a8-b78b-f28e7a3ce001)
</picture>

+ Getting the hash of the file downloaded to analyze.

<picture>![image](https://github.com/user-attachments/assets/263d3a18-bc4b-42ef-86b0-35764f06e052)
</picture>

+ Using the hash obtained in virustoral to check the state of the file.
  ++ Link: https://www.virustotal.com/gui/file/41c3dd4e9f794d53c212398891931760de469321e4c5d04be719d5485ed8f53e  
<picture>![image](https://github.com/user-attachments/assets/9099bcd2-2994-43d7-87fb-5c297d187aeb)
</picture>

+ The description of what the file can cause is described below.
  
<picture>![image](https://github.com/user-attachments/assets/61a4aef3-b109-42c9-9edd-d060241f4638)
</picture>

+ Let’s find out what are embedded in the word doc file using the ‘**oledump.py**’ tool. 

<picture>![image](https://github.com/user-attachments/assets/e9811bc4-acc4-4a32-86e1-5ee9c8dc6350)
</picture>

+ Running the script together with other arguments prints out the content of the vba script.  
<picture>![image](https://github.com/user-attachments/assets/ae7fd7c4-9161-4a5c-b11d-2f400d16c7b3)
</picture>

+ I pasted the script in ‘Deepseek generative AI’ tool to explain the code for me and it tells me it is malicious.  
<picture>  ![image](https://github.com/user-attachments/assets/339666c6-fb06-410f-9890-1cd10e38d31d)
</picture>
<picture>![image](https://github.com/user-attachments/assets/d892dbac-609a-4d87-bf5f-ac0124fdefac)
</picture>
<picture>![image](https://github.com/user-attachments/assets/4a3d87a0-be7d-41ce-b2d5-79e218f6901e)
</picture>


<picture></picture>


<picture></picture>


<picture></picture>


<picture></picture>


<picture></picture>

<picture></picture>

<picture></picture>
