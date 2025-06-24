# In this Active Directory Lab I'll be Dealing with Group Policies and Managing Accounts  Account Lockouts,Enabling and Disabling Accounts and Observing Logs in Group Policy
--
Part 3: Account Lockouts & Security Logs
Steps
1. Simulate 10 Failed Logins on Client-1
24_failed_logins_10_attempts.png
2. Configure Lockout Policy in Group Policy
• Threshold: 5 attempts, Duration: 15 mins ro 25_account_lockout_gpo_config.png roi 26_gpupdate_force_run.png
3. Trigger Lockout with 6 Failed Logins o27_account_lockout_error.png
4. Unlock and Reset User Password in ADUC
28_account_locked_in_aduc.png
129_unlock_and_reset_password.png
9 30
_successful_login_after_unlock.png
5. Disable and Re-enable User Account
31_account_disabled_aduc.png
132. _disabled_login_error.png
$ 33
_account_reenabled_successful_login.png
6. View Security Logs on DC and Client
• DC Logs: 4625, 4740
134_event_log_account_locked_dc.png
$ 35
_failed_logins_client_logs.png
