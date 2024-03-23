# Email-phishing
 



  This is an email phishing tool which uses Social engineering trick to send phishing links or malicious


  Payload to your victim targeted email address


  This updated version now consist of single mailer and mass mailer too


  You can also send malicious attachment with this mailer 


  The message is delivered to the victim inbox in plain not html format

  
  This mailer support all version of SMTP server and port except gmail smtp server and port


  Since nearly all SMTP server uses port 587 support TLS except gmail SMTP which uses depreciated port 456 and support SSL

 
  To use the Mass mailer tool just input the list of those email address in email.txt file and run

 
 

  Pls dont send to the wrong email address 

 
# Commands


 


 git clone https://github.com/Gbolahanomotosho/Email-phishing


 cd Email-phishing



 pip3 install -r requirements.txt







 For single mailer:

 
 python3 Email-phishing.py
 

 python3 Email-phishing-with-attachment.py






 For mass mailer:

 Input all victim email address list in email.txt

 Then type

 python3 Mass-mailer.py

 python3 Mass-mailer-with-attachment.py

 


# To Use:




 Enter your SMTP server, port and SMTP username and password


 But for mass mailer 


 Enter your email address in email.txt then enter your SMTP server, port and SMTP username and password


 And follow the rest of instructions shown on the terminal


 Happy email phishing.......






 If you want your mailer to deliver crafted message in html format


 You can contact the developer for it but it is going to be a premium version


 All this mailer either single or mass mailer hit victim inbox 100% 




# tested on :




- Linux


- Windows 


- Termux

 

# Disclaimer:



  I wont be responsible for malicious use of this tool



  Any misuse of this tool is strictly your responsibility



 And dont send to the wrong email address
