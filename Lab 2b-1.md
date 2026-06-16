# Part A: Create an Ubuntu VM on AWS and install Apache, ending with testing the default Apache landing page.

Create Amazon EC2 web services account and launch an instance

<img width="600" height="300" alt="Screenshot 2026-06-17 042642" src="https://github.com/user-attachments/assets/a0c064eb-9a95-4970-a28c-665a562df639" />

<img width="800" height="700" alt="Screenshot 2026-06-17 043001" src="https://github.com/user-attachments/assets/c101059b-12ce-4dd8-bccf-8f6bdba12982" />

<img width="800" height="770" alt="Screenshot 2026-06-17 043511" src="https://github.com/user-attachments/assets/70a76aba-5582-4938-a496-d36e9b84037e" />

Faced an error while trying to connect the AWS EC2 

<img width="800" height="312" alt="Screenshot 2026-06-17 043634" src="https://github.com/user-attachments/assets/4f1415f5-5fe5-4681-b966-6908dfbac2c8" />


Chatgpt to check on what is the error. Connecting the SSH to EC2 instance

<img width="800" height="600" alt="Screenshot 2026-06-17 044217" src="https://github.com/user-attachments/assets/e42de2b2-1d11-4f6b-a311-cc0fb12f4765" />

<img width="600" height="400" alt="Screenshot 2026-06-17 045131" src="https://github.com/user-attachments/assets/ad4ab382-db73-4774-a729-149c979aab7c" />

Install Apache Web Server and Status is active (running)

<img width="800" height="600" alt="Screenshot 2026-06-17 045148" src="https://github.com/user-attachments/assets/2e70ad69-ef67-45d4-83f5-ee8f93f591b4" />

<img width="600" height="800" alt="Screenshot 2026-06-17 045755" src="https://github.com/user-attachments/assets/c1af65d5-fc63-4858-944d-3528d1e6b8cf" />

Replace default page as sudo nano /var/www/html/index.html and Ran into an error while trying to save my webpage. 

<img width="617" height="120" alt="Screenshot 2026-06-17 051457" src="https://github.com/user-attachments/assets/f8f5943a-9951-4895-9359-b88f3301abcb" />

Notice that I have omitted the word sudo in the command line hence unable to save to the folder.

<img width="800" height="285" alt="Screenshot 2026-06-17 051628" src="https://github.com/user-attachments/assets/aa828123-2c1f-4163-b83a-08a1afe3db6a" />

<img width="800" height="443" alt="Screenshot 2026-06-17 052955" src="https://github.com/user-attachments/assets/e168de84-a8c4-48de-b3fa-6889005eccc4" />



Once I have completed everything, I stop the AWS EC2 instances in order to prevent incurring charges.

<img width="600" height="485" alt="Screenshot 2026-06-17 051918" src="https://github.com/user-attachments/assets/9be1045c-7392-4a30-b264-988b407372db" />



# Part B - Azure account signups and Create a Linux Virtual Machine (Azure) 

<img width="800" height="447" alt="Azure" src="https://github.com/user-attachments/assets/330227f9-4ebf-40cf-9810-09605dee87a6" />

<img width="800" height="600" alt="Screenshot 2026-06-17 055045" src="https://github.com/user-attachments/assets/542bc793-c61f-4c0a-aff1-f72921193d09" />

<img width="800" height="600" alt="Screenshot 2026-06-17 055216" src="https://github.com/user-attachments/assets/c4e1eb7c-78c9-49fd-9a14-834b73e7e506" />

Customizing the webpage and this time I did not forget about the sudo.

<img width="800" height="426" alt="Screenshot 2026-06-17 055421" src="https://github.com/user-attachments/assets/6992f40b-5456-4c51-b7ac-d5dd724fd2fe" />

<img width="800" height="486" alt="Screenshot 2026-06-17 055654" src="https://github.com/user-attachments/assets/9b9772de-846d-44b5-b24f-e16d6a70f926" />

After completed, I stop the azure VM to prevent incurring charges.

<img width="800" height="331" alt="Screenshot 2026-06-17 060155" src="https://github.com/user-attachments/assets/50176f6b-d912-4608-b513-3a617352fd91" />



What did I learn from this lab? 
AWS EC2 and Azure allows users to create virtual servers in the cloud while SSH provides secure remote access to Linux servers. I get to practice both and what I had learnt, they both work almost the same way. 
Apache can host websites accessible through a public IP address and also security groups act as firewalls by controlling network traffic.
Ubuntu Server is a lightweight Linux operating system suitable for web hosting
