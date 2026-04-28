UMASK =>default permissions 


4=read(r)
2=write(w)
1=execute(x)
4+2+1=7 full permissions 


____           rwx      rwx      rwx 
file type      user     group    other 

owner u
group g 
other o
all   a

chmod =>change mode 
chmod 755 file.txt ==> for file.txt user have full permission , group and other will have read and execute , no write option 

chmod go-wx => group and other have no write and execute only read 

chown => change owner 
chgrp => change group 

