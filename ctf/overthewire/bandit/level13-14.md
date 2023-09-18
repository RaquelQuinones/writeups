## Level 13-14
# Analysis

The password for the level 14 it is stored in /ect/bandit_pass/bandit14 and it can only be read by the user bandit14. But we are login as bandit13. 
We are given the private SSH ket which can be used to log in into the next level, with the hostname localhost.
```
ssh -i <privatekey> bandit14@localhost -p 2220
```
Now, enter the directories to find the password:  ***/ect/bandit_pass/bandit14***

## Flag
```
fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq
```
