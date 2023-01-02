# Runbook to setup blog
0. Backup the original blog using a WordPress plugin.
1. Create a new instance.
2. Login and activiate the anti-spam plugin.
3. Import the backup to the new site.
4. Detach the static IP from the old instance and attach it to the new instance.
5. Create a SSL certificate for the new site.
6. Create a cron job to renew the SSL certificate periodically .
7. Create a snapshot for the new instance.
8. Setup alarms for the new instance.
9. Delete the old instance and its snapshot.