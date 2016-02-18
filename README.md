source : https://wiki.postgresql.org/wiki/Automated_Backup_on_Linux

Then add this to your anacron

`1   15	 cron.daily   path/to/script/pg_backup_rotated.sh`
