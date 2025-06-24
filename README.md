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
📸 28_account_locked_in_aduc.png
📸 29_unlock_and_reset_password.png
📸 30_successful_login_after_unlock.png

5.Disable and Re-enable User Account
📸 31_account_disabled_aduc.png
📸 32_disabled_login_error.png
📸 33_account_reenabled_successful_login.png

6.View Security Logs on DC and Client
•DC Logs: 4625, 4740
📸 34_event_log_account_locked_dc.png
📸 35_failed_logins_client_logs.png
