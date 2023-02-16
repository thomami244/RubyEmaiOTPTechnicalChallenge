# RubyEmaiOTPTechnicalChallenge
This is a response to a technical challenge to implement an email OTP module to be used for an enterprise application. 

I could use any language, and chose to use Ruby due to development speed under a tight deadline.

In order to exectute the file using the command line:
1. Save the file to your local hard disk
2. Download Ruby compiler 
3. Execute the file by typing "ruby [path of the file on your local hard disk]"

Features:
- A random 6 digit OTP is sent to a user that enters a "@gmail.com" email account (you can change the email required in the regex statement)
- The user is logged out after 10 failed attempts to input OTP
- The OTP expires after 1 minute

Success:

<img width="392" alt="image" src="https://user-images.githubusercontent.com/84807009/219258970-b2248b58-a0a1-46ff-84ab-23107d48d1ab.png">


A random 6 digit OTP is sent to a user that enters an "@gmail.com" email account:

<img width="480" alt="image" src="https://user-images.githubusercontent.com/84807009/219258260-60116647-b26d-4943-bc5f-0d1474c794a7.png">

The user is logged out after 10 failed attempts to input OTP:

<img width="395" alt="image" src="https://user-images.githubusercontent.com/84807009/219259668-247a2379-d626-4316-be11-67827d0618b8.png">

The user is logged out after 1 minute:

<img width="401" alt="image" src="https://user-images.githubusercontent.com/84807009/219259432-866edb09-081c-405d-8c6c-da0c4534c080.png">





