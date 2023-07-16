# minimalist-web-calendar
calendar utelizing [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad).

1. Copy calendar.html to /var/www/html
   > 396218 -rw-r--r-- 1 root     root     8125 Jul 10 19:46 calendar.html

2. Copy REPEATING to /var/www/html/_tmp
3. Copy NONREPEATING to /var/www/html/_tmp

2. Change line 7 and 8 to reflect the address of your server and the 2 notepad files to be used:
  - REPEATING - for events that repeat on a monthly or weekly basis
  - NONREPEATING - for single date events
