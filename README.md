# In this Active Directory Lab I'll be Dealing with Group Policies and Managing Accounts  Account Lockouts,Enabling and Disabling Accounts and Observing Logs in Group Policy
--
🔐 Part 3: Account Lockouts & Security Logs

✅ Steps
1.Simulate 10 Failed Logins on Client-1
📸 24_failed_logins_10_attempts.png

2.Configure Lockout Policy in Group Policy
•Threshold: 5 attempts, Duration: 15 mins
📸 ![image](https://github.com/user-attachments/assets/e83ad67f-26ce-41e4-ac57-9d2cbda6d507)
![image](https://github.com/user-attachments/assets/6eaac35f-b4ba-430e-8298-4dc524728a27)

📸![image](https://github.com/user-attachments/assets/adcca128-3215-4d35-a882-85dc4b015594) gpupdate_force_run.png

![image](https://github.com/user-attachments/assets/1aca7edf-0e07-4e28-a160-0a1d70999b05)

3.Trigger Lockout with 6 Failed Logins
📸 27_account_lockout_error.png

4.Unlock and Reset User Password in ADUC
📸 ![image](https://github.com/user-attachments/assets/ea3c781a-01b6-4a48-9602-3dc34b8c45bf)

📸 29![image](https://github.com/user-attachments/assets/5ffafbe0-05d5-4f79-8231-cc404553d97a)

📸 30_successful_login_after_unlock.png

5.Disable and Re-enable User Account
📸 ![image](https://github.com/user-attachments/assets/e7502a14-4d6f-46a1-b908-dfb011645123)

📸 32_disabled_login_error.png
📸 ![image](https://github.com/user-attachments/assets/1338ca80-479b-45e3-88af-24a1ec758da6)


6.View Security Logs on DC and Client
•DC Logs: 4625, 4740
📸 ![image](https://github.com/user-attachments/assets/0e3d01c6-3cbc-492b-b110-ee02ef9b2f19)

📸 35_failed_logins_client_logs.png
