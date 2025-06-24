# In this Active Directory Lab I'll be Dealing with Group Policies and Managing Accounts  Account Lockouts,Enabling and Disabling Accounts and Observing Logs in Group Policy
--
🔐 Part 3: Account Lockouts & Security Logs

✅ Steps
	1.	Simulate 10 Failed Logins on Client-1
📸 24_failed_logins_10_attempts.png
	2.	Configure Lockout Policy in Group Policy
	•	Threshold: 5 attempts, Duration: 15 mins
📸 25_account_lockout_gpo_config.png
📸 26_gpupdate_force_run.png
	3.	Trigger Lockout with 6 Failed Logins
📸 27_account_lockout_error.png
	4.	Unlock and Reset User Password in ADUC
📸 28_account_locked_in_aduc.png
📸 29_unlock_and_reset_password.png
📸 30_successful_login_after_unlock.png
	5.	Disable and Re-enable User Account
📸 31_account_disabled_aduc.png
📸 32_disabled_login_error.png
📸 33_account_reenabled_successful_login.png
	6.	View Security Logs on DC and Client
	•	DC Logs: 4625, 4740
📸 34_event_log_account_locked_dc.png
📸 35_failed_logins_client_logs.png
