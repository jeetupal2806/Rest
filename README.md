# Rest
Backend api's are not ready. Don't curse backend dev's , create your own Rest api for unstoppable android development.

Example:
http://192.168.1.129:8080/greeting

/********
Notes:
If you get error( like 404 - Nginx ) on submitting this url on browser "http://192.168.1.129:8080/greeting" 
i.e Nginx is working on 8080
 ps -ax | grep 'nginx'

➜  ~ ps -ax | grep 'nginx'
  542 ??         0:00.03 nginx: master process /usr/local/opt/nginx/bin/nginx -g daemon off;
  636 ??         0:00.01 nginx: worker process
 1411 ttys000    0:00.00 grep --color=auto --exclude-dir=.bzr --exclude-dir=CVS --exclude-dir=.git --exclude-dir=.hg --exclude-dir=.svn nginx
➜  ~ kill -9 542
➜  ~ kill -9 1411
kill: kill 1411 failed: no such process
➜  ~ ps -ax | grep 'nginx'
 1432 ttys000    0:00.00 grep --color=auto --exclude-dir=.bzr --exclude-dir=CVS --exclude-dir=.git --exclude-dir=.hg --exclude-dir=.svn nginx
➜  ~ kill -9 1432'
quote>

=================== Shortcut to search and close port =====================
➜  ~ lsof -i :8080 | grep LISTEN
java    7592 jeetupal   61u  IPv6 0xc2f5b2aec1b3ab67      0t0  TCP *:http-alt (LISTEN)
-> kill -9 7592
============================================================

conversion json respone to place in Noderesponse.java file
******* Logic : replace this —> “  with “/
http://www.unit-conversion.info/texttools/replace-text/
