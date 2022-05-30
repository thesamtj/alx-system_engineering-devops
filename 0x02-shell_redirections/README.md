#Shell I/O Redirection Exercises

NOTE: Why does the following happen?

### list all files/directories in current working directory and all sub-directories

vagrant@vagrant-ubuntu-trusty-64:~/samuel$ ls -laR
.:
total 16
drwxrwxr-x 4 vagrant vagrant 4096 May  30 00:00 .
drwxr-xr-x 7 vagrant vagrant 4096 May  30 19:34 ..
-rw-rw-r-- 1 vagrant vagrant    0 May  30 23:07 10-no_more_js
-rw-rw-r-- 1 vagrant vagrant    0 May  30 00:00 a.js
drwxrwxr-x 3 vagrant vagrant 4096 May  30 00:00 dir1
drwxrwxr-x 2 vagrant vagrant 4096 May  30 00:00 dir.js
-rw-rw-r-- 1 vagrant vagrant    0 May  30 21:21 .gitignore
-rw-rw-r-- 1 vagrant vagrant    0 May  30 23:07 hello
-rw-rw-r-- 1 vagrant vagrant    0 May  30 23:07 iacta
-rw-rw-r-- 1 vagrant vagrant    0 May  30 23:07 ls_cwd_content

./dir1:
total 12
drwxrwxr-x 3 vagrant vagrant 4096 May  30 00:00 .
drwxrwxr-x 4 vagrant vagrant 4096 May  30 00:00 ..
drwxrwxr-x 3 vagrant vagrant 4096 May  30 00:00 acedir
-rw-rw-r-- 1 vagrant vagrant    0 May  30 00:00 b.js
-rw-rw-r-- 1 vagrant vagrant    0 May  30 23:39 hello

./dir1/acedir:
total 12
drwxrwxr-x 3 vagrant vagrant 4096 May  30 00:00 .
drwxrwxr-x 3 vagrant vagrant 4096 May  30 00:00 ..
-rw-rw-r-- 1 vagrant vagrant    0 May  30 00:00 c.js
drwxrwxr-x 2 vagrant vagrant 4096 May  30 23:58 hi

./dir1/acedir/hi:
total 8
drwxrwxr-x 2 vagrant vagrant 4096 May  30 23:58 .
drwxrwxr-x 3 vagrant vagrant 4096 May  30 00:00 ..

./dir.js:
total 8
drwxrwxr-x 2 vagrant vagrant 4096 May  30 00:00 .
drwxrwxr-x 4 vagrant vagrant 4096 May  30 00:00 ..
-rw-rw-r-- 1 vagrant vagrant    0 May  30 00:00 d.js




----