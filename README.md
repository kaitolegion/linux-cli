# linux-cli
Linux Commands Resources | Tips & Tricks by @Kaito-Coding


### Basic commands
```sh
#
ls
ls -alps
ls -la
# calculator
cal
# 
neofetch
# find dns
traceroute xkaito.com
# simple mathematics
echo "8*8" | bc
# show history previous commands
history
# shutdown your machine
sudo shutdown -h now
```
### Advance Commands
- touch
```sh
# create file
touch file.txt
# create file in the future
touch -d tomorrow file.txt
```
- echo
```sh
# creating file
echo 'kaito coding' > file.txt
```
- shred
```sh
# overwrite a file to hide its contents, and optionally delete it
shred file.txt
```
- whatis
```sh
# display brief description of command or function
whatis curl
whatis wget
whatis git
```
- zip
```sh
# zip a file
zip new.zip file.txt
# zip a folder
zip new.zip -r folder
# unzip file or folder
unzip new.zip
```
- cmp & diff
```sh
# compare two files
cmp file1.txt file2.txt
diff file1.txt file2.txt
```
- sort
```sh
# sort file to alphabetical order
cat file.txt | sort 
```
- find
```sh
# find a file name 
find / -name "kaito*"
# find all hidden files
find . -type f -name ".*"
# find all empty directories
find . -type f -empty
# find all executable files
find . -perm /a=x
```
- grep
```sh
# find all ip address
ifconfig | grep -oE "inet [0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}"

```
