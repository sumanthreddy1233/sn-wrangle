# Bonus-Challenge
## Speaker 1
SATURNINUS
## Speaker 2
BASSIANUS
## Questions asked
* How many times did speaker 1 spoke?
* How many times did speaker 2 spoke?
* Total number of times both the speakers spoke?(number of times spoken by speaker 1+ number of times spoken by speaker 2)
## Commands used to get the answer
* $ grep -i '^SATURNINUS' input.txt -c -nr>SATURNINUSCOUNT.txt

* $ grep -i '^BASSIANUS' input.txt -c -nr>BASSIANUSCOUNT.txt

* According to my knowledge that I got from google we can't aggregate two counts at a time using bash commands.
## Answers 
* 50
* 14
* 64

