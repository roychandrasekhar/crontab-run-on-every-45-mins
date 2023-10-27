# crontab-run-on-every-45-mins
Run crontab job in every 45 mins

Open the crontab for the user, 
Lets assume we are just adding server time in the fix file to test if its log in every 45 mins or not

Crontab content
```
00 */3 * * * date >> /var/www/projects/academylive/testtime.txt
45 */3 * * * date >> /var/www/projects/academylive/testtime.txt
30 */3 * * * date >> /var/www/projects/academylive/testtime.txt
15 */3 * * * date >> /var/www/projects/academylive/testtime.txt
```

Output after the cron run on schedule</br>
![](https://i.imgur.com/r0TMC9y.png)
