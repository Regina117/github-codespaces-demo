#github-codespaces-demo
this is for a demo

#what file entries 1005
ls -l /usr/bin | wc -l 
#create file with 1005
ls -l /usr/bin | wc -l > bin.txt
#white in the newfile-lines
echo "$STR" > lines.txt

#what have in the efile
cat lines.txt
#number 3
cat lines.txt |grep 3

#write in file
echo "only 1 word or rewrite word" > append.txt
echo "next word" >> append.txt

tail -f /var/log/dpkg.log
tail -n 2 /var/log/dpkg.log
#all command
history | less 
history | grep tail
#!
#!!