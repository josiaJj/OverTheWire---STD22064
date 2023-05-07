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
