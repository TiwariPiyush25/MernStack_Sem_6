# Unix Commands

pwd              -> show current directory  
ls               -> list files  
ls -l            -> long list format  
ls -a            -> show hidden files  
cd folder        -> change directory  
cd ..            -> move back one directory  
mkdir dir        -> create folder  
rmdir dir        -> delete empty folder  
rm file          -> delete file  
rm -r dir        -> delete folder with contents  
touch a.txt      -> create file  
cp a.txt b.txt   -> copy file  
mv a.txt b.txt   -> rename/move file  

cat a.txt        -> read file  
more a.txt       -> read file page wise  
less a.txt       -> scroll file  
head a.txt       -> first 10 lines  
tail a.txt       -> last 10 lines  
tail -f log.txt  -> live file output  

man ls           -> manual of command  
help             -> help for shell  
ls --help        -> command usage  

whoami           -> current user  
who              -> logged in users  
date             -> current date and time  
cal              -> calendar  
uname            -> system info  

ps               -> running processes  
top              -> live process view  
kill pid         -> stop process  
jobs             -> background jobs  
bg               -> run job in background  
fg               -> bring job to foreground  

df               -> disk usage  
du               -> directory size  
free             -> memory usage  
uptime           -> system running time  

grep word file.txt       -> search word in file  
sort file.txt            -> sort file  
uniq file.txt            -> remove duplicates  
wc file.txt              -> count lines, words, chars  
cut -d":" -f1 file.txt   -> cut column  
tr a-z A-Z               -> convert lowercase to uppercase  

find . -name "*.txt"     -> find txt files  
locate file.txt          -> search file  
which ls                 -> path of command  
whereis ls               -> location of command  

chmod 777 file           -> change permission  
chown user file          -> change owner  
chgrp group file         -> change group  

ping google.com          -> check network  
ip addr                  -> show IP address  
ssh user@host            -> remote login  
scp a.txt user@host:/dir -> copy to remote  

tar -cvf a.tar file      -> create tar  
tar -xvf a.tar           -> extract tar  
zip a.zip file           -> compress file  
unzip a.zip              -> extract zip  
gzip file                -> compress  
gunzip file.gz           -> decompress  

ls > out.txt             -> redirect output  
ls >> out.txt            -> append output  
wc < file.txt            -> input redirection  
ls | grep txt            -> pipe output
