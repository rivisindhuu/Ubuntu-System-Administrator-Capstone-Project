# Ubuntu-System-Administrator-Capstone-Project


________________________________________
## 1. System Setup (Ubuntu Installation)

 <img width="939" height="884" alt="image" src="https://github.com/user-attachments/assets/a9916465-6df1-47f3-9f3b-ebcb9cdc339a" />

________________________________________
## 2. Create User Accounts
Creating two users
2.1 User 1
 <img width="939" height="669" alt="image" src="https://github.com/user-attachments/assets/f76670aa-e6b1-4734-b762-cf082ea2a5d9" />

2.2 User2
 <img width="939" height="555" alt="image" src="https://github.com/user-attachments/assets/3e5e50ef-c56f-433a-8474-29206101f4ec" />

2.3 Give admin rights to user1
 <img width="844" height="47" alt="image" src="https://github.com/user-attachments/assets/893de813-0b3f-439d-a603-47d05a4ba1d2" />

2.4 Verify users
<img width="847" height="81" alt="image" src="https://github.com/user-attachments/assets/962a4e48-4c99-479b-94af-b366f0f0aecc" />

 ________________________________________
## 3. Networking Configuration
3.1 Check current IP
 <img width="939" height="409" alt="image" src="https://github.com/user-attachments/assets/f2a3bb67-4fec-463e-9767-ed1e71fa5669" />

________________________________________
3.2 Assign Static IP  
<img width="878" height="623" alt="image" src="https://github.com/user-attachments/assets/6ce19d7a-6712-438c-bb97-2e80e606ca3e" />

3.3 Apply changes:
 
<img width="838" height="48" alt="image" src="https://github.com/user-attachments/assets/b6e800d7-c643-414d-80d3-8f2f13d65567" />

________________________________________
## 4. Network Diagnostics

 
4.1 Ping test
4.1.1 
 <img width="866" height="206" alt="image" src="https://github.com/user-attachments/assets/44974f30-f0b9-4c3a-9273-55eb3c4c49e5" />
 4.1.2
 <img width="902" height="77" alt="image" src="https://github.com/user-attachments/assets/2da9dd98-9356-496c-9d4d-ba981f60fe46" />


4.2.1 Traceroute
Traceroute was not found so I had to install it 
 <img width="875" height="123" alt="image" src="https://github.com/user-attachments/assets/16a16ce1-af91-4ff4-918c-29efd40cb696" />

4.2.2 Traceroute install
 
<img width="858" height="536" alt="image" src="https://github.com/user-attachments/assets/2b0378ea-0be1-412f-8bae-511571031c0c" />


4.2.3 Traceroute output 
 <img width="941" height="367" alt="image" src="https://github.com/user-attachments/assets/cd98e0bd-7d1e-4149-96d2-89130051d237" />

4.3 Ifconfig

 <img width="888" height="92" alt="image" src="https://github.com/user-attachments/assets/8f5291b4-fa76-40b5-8aab-e8b74b396c66" />


4.3.2 I had to install ifconfig since it was missing.
 <img width="872" height="183" alt="image" src="https://github.com/user-attachments/assets/8568439a-fc93-4ac5-970b-488366c7546e" />

4.3.3 ifconfig output 
 <img width="941" height="483" alt="image" src="https://github.com/user-attachments/assets/e44008a3-cf08-416d-9867-2a16ddbc1272" />

________________________________________
## 5. Install Web Server (Apache)
5.1 Apache2 update
 
<img width="939" height="381" alt="image" src="https://github.com/user-attachments/assets/1913c7aa-09bb-4b56-b916-3111f9e8c3fe" />


5.2 Installing apache2
 
<img width="940" height="444" alt="image" src="https://github.com/user-attachments/assets/996cae44-cce4-4053-a567-56124065b03f" />

5.3 Apache2 status check:
 <img width="941" height="461" alt="image" src="https://github.com/user-attachments/assets/8fb139cb-cee2-4271-91e7-b51d94fd6c76" />


5.4 Open browser:
<img width="939" height="720" alt="image" src="https://github.com/user-attachments/assets/b77343a9-961a-4afa-9b7e-11ca65165876" />

 ________________________________________
## 6. Create Local Intranet Page
6.1 Edit default webpage:
 
<img width="939" height="448" alt="image" src="https://github.com/user-attachments/assets/cccd3030-6d5a-4bdf-9a19-93215528aebf" />


6.2 The page after editing.
 <img width="939" height="333" alt="image" src="https://github.com/user-attachments/assets/e8518c44-dff4-4dbc-887e-d6f1a43d0143" />

________________________________________
## 7. File Sharing with Samba

7.1 Installing samba
 <img width="939" height="631" alt="image" src="https://github.com/user-attachments/assets/ddccaa3b-c20d-441d-81eb-3ea2e4fdd03e" />

7.2 Creating a shared directory:
 <img width="941" height="102" alt="image" src="https://github.com/user-attachments/assets/f2fbddae-7f21-45f4-ab4e-57e4dff45733" />

7.3 Edit Samba config:
 <img width="855" height="44" alt="image" src="https://github.com/user-attachments/assets/0b2a589e-95de-4eae-baee-8ec0be87b850" />

________________________________________
## 8. Security Configuration
8.1 Enable Firewall
 <img width="769" height="214" alt="image" src="https://github.com/user-attachments/assets/d26ab06b-770e-475b-b6df-4268b8d3d592" />

8.2 Allow Apache: 
<img width="803" height="109" alt="image" src="https://github.com/user-attachments/assets/748c9a2b-1706-4d39-ae5c-90c4447bd937" />
___________________________________
8.3 sudo apt install  
<img width="941" height="395" alt="image" src="https://github.com/user-attachments/assets/f0f1cb30-863c-4995-a202-868ccf8cfbd7" />

8.5 Run scan: 
________________________________________
## 9. Troubleshooting Log (for submission)

Date	|Issue	|Diagnosis	|Solution	|Result
24 Mar|Apache not loading|	Service stopped	|Restarted apache2	|Working
24 Mar|No internet|	Interface down|	Enabled interface	|Fixed
________________________________________
## 10. Network/System Diagram
 
__<img width="941" height="634" alt="image" src="https://github.com/user-attachments/assets/77c83ffd-c990-44b2-9bf6-1d0a6d857e2b" />
______________________________________
11. Reflection 
This project helped me understand Linux system administration, including user management, network configuration, firewall setup, and web server deployment. I learned how to troubleshoot services using systemctl and diagnose network problems using ping and traceroute. If I repeated this project, I would automate the setup using shell scripts or Ansible.

