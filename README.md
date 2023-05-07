# OverTheWire---STD22064
[OverTheWire Bandit](https://overthewire.org/wargames/bandit/)  
port : 2220  

## LEVEL 0  
`ssh bandit0@bandit.labs.overthewire.org -p 2220`  
password : **bandit0**  

## LEVEL 0 -> LEVEL 1  
`ls`
`cat readme`  
password for Level 1 : **NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL**  
`ssh bandit1@bandit.labs.overthewire.org -p 2220`

## LEVEL 1 -> LEVEL 2
`ls`
`cat ./-`  
password for Level 2 : **rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi**  
`ssh bandit2@bandit.labs.overthewire.org -p 2220`  

## LEVEL 2 -> LEVEL 3
`cat "spaces in this filename"`  
password for Level 3 : **aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG**  
`ssh bandit3@bandit.labs.overthewire.org -p 2220`  

## LEVEL 3 -> LEVEL 4
`ls`
`cd inhere/`
`ls -a`
`cat ./.hidden`  
password for Level 4 : **2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe**  
`ssh bandit4@bandit.labs.overthewire.org -p 2220`

## LEVEL 4 -> LEVEL 5
`ls`
`cd inhere/`
`ls`
`cat ./-file07`  
password for Level 5 : **lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR**  
`ssh bandit5@bandit.labs.overthewire.org -p 2220`

## LEVEL 5 -> LEVEL 6
`ls`
`cd inhere/`
`find . -type f -readable -size 1033c ! -executable`
`cat ./maybehere07/.file2`  
password for Level 6 : **P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU**  
`ssh bandit6@bandit.labs.overthewire.org -p 2220`

## LEVEL 6 -> LEVEL 7
`find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null`
`cat /var/lib/dpkg/info/bandit7.password`  
password for Level 7 : **z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S**  
`ssh bandit7@bandit.labs.overthewire.org -p 2220`  

## LEVEL 7 -> LEVEL 8
`grep "millionth" data.txt`  
password for Level 8 : **TESKZC0XvTetK0S9xNwm25STk5iWrBvP**  
`ssh bandit8@bandit.labs.overthewire.org -p 2220`

## LEVEL 8 -> LEVEL 9
`sort data.txt | uniq -u`   
password for Level 9 : **EN632PlfYiZbn3PhVK3XOGSlNInNE00t**  
`ssh bandit9@bandit.labs.overthewire.org -p 2220`

## LEVEL 9 -> LEVEL 10
`strings data.txt | grep "^=.*"``   
password for Level 10 : **G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s**  
`ssh bandit10@bandit.labs.overthewire.org -p 2220`  

## LEVEL 10 -> LEVEL 11
`base64 -d data.txt`  
password for Level 11 : **6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM**  
`ssh bandit11@bandit.labs.overthewire.org -p 2220`  
