# **General Linux Concept Using OverTheWire Bandit**

### OverTheWire Bandit is a wargame to understand the basic commands to navigate in Linux/Unix environmen.

-------

## Stetup

* Go to https://overthewire.org/wargames/bandit/
* Open Temrminal and remotey connect to the host
* ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit0 ```
* To prove the authenticity of the host type ```yes```
* Entered password ```bandit0```

-----------
### Level 0
1. Type ```ls``` 
2. To read the file ```cat readme```
3. The password for bandit1 is stored in this file and the passwrd is```boJ9jbbUNNfktd78OOpsqOltutMc3MY1```


### Level 1
1. ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit1 ```
2. Enter the password retrived from level 0 
3. ```ls```
4. ```cat ./-```
5. The password for bandit2 is stored in this file and the passwrd is```CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9```


### Level 2 
1. ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit2 ```
2. Enter the password retrived from level 1
3. ```ls```
4. ```ls -al```
5. ```cat 'spaces in this filename' ```
6. The password for bandit3 is stored in this file and the passwrd is```UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK```


### level 3
1.  ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit3 ```
2. Enter the password retrived from level 2
3. To change the current directory into inhere ```cd inhere```
4. ```ls -al```
5. ```cat .hiddeny```
6. The password for bandit4 is stored in this file and the passwrd is```pIwrPrtPN36QITSp3EQaw936yaFoFgAB```


### Level 4 
1.  ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit4 ```
2. Enter the password retrived from level 3
3. ```ls```
4. ```cd inhere```
5. ```ls -al```
6. To see the human readable file or ASCII text ```file -- *```
7. The password for bandit5 is stored in this file and the passwrd is ```koReBOKuIDDepwhWk7jZC0RTdopnAYKh```


### level 5
1. ``` ssh bandit.labs.overthewire.org -p 2220 -l bandi5 ```
2.  Enter the password retrived from level 4
3. ```ls```
4. to find file by size ```find -size 1033c```
5. ```cat ./maybehere07/.file2```
6.  The password for bandit6 is stored in this file and the passwrd is ``` DXjZPULLxYr17uwoI01bNLQbtFemEgo7```


### Level 6
1. ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit6 ```
2. Enter the password retrived from level 5
3. ```cd ..```
4. ```cd ..```
5. ```find -size 33c```
6. copy ```/var/lib/dpkg/info/bandit7.password```
7. ```cat /var/lib/dpkg/info/bandit7.password```
8. the password is ```HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs```


### Level 7 
1. ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit7 ```
2. ```ls```
3. ```grep "millionth" data.txt```
4. ```cvX2JJa4CFALtqS87jk27qwqGhBM9plV```


### level 8 sort data
1. ``` ssh bandit.labs.overthewire.org -p 2220 -l bandit8 ```
2. ```ls ```
3. ```sort data.txt | uniq -u ```
4. ``` UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR ```


### Level 9 
1. ```ssh bandit.labs.overthewire.org -p 2220 -l bandit9 ```
2. ``` ls ```
3. ```strings data.txt | grep = ```
4. ``` truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk ```


### level 10 decoding
1. ```ssh bandit.labs.overthewire.org -p 2220 -l bandit10 ```
2. ```ls```
3. ```cat data.txt ```
4. copy the encoding string ```VGhlIHBhc3N3b3JkIGlzIElGdWt3S0dzRlc4TU9xM0lSRnFyeEUxaHhUTkViVVBSCg==```
5. ```echo -n 'VGhlIHBhc3N3b3JkIGlzIElGdWt3S0dzRlc4TU9xM0lSRnFyeEUxaHhUTkViVVBSCg==' | base64 decode ```
6. the decoded string or paswwrd is ```IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR```


### Level 11 
1. ```ssh bandit.labs.overthewire.org -p 2220 -l bandit11 ```







