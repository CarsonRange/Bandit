# Bandit Level 0

`ssh -p 2220 bandit0@bandit.labs.overthewire.org`

bandit0

# Bandit Level 1

`cat readme`

boJ9jbbUNNfktd78OOpsqOltutMc3MY1

# Bandit Level 2

`cd ~/-`

CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

# Bandit Level 3

`cat ~/spaces\ in\ this\ filename`

UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

# Bandit Level 4

``` 
cd inhere/
ls -lah
cat .hidden
```

pIwrPrtPN36QITSp3EQaw936yaFoFgAB

# Bandit Level 5

`cd inhere/`
`ls -lah`
`head ./-file07`

koReBOKuIDDepwhWk7jZC0RTdopnAYKh

# Bandit Level 6

```
find . -size 1033c
cat ~/inhere/maybehere07/.file2
```

DXjZPULLxYr17uwoI01bNLQbtFemEgo7

# Bandit Level 7

```
find -user bandit7 -group bandit6 -size 33c
cat ./var/lib/dpkg/info/bandit7.password
```

HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs


# Bandit Level 8

```
cat data.txt | grep millionth
```

cvX2JJa4CFALtqS87jk27qwqGhBM9plV

# Bandit Level 9

```
sort data.txt | uniq -u -c
```

UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

# Bandit Level 10

```
strings data.txt
strings data.txt | grep ^=
strings data.txt | grep ==========
```

truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

# Bandit Level 11

```
man base64
cat data.txt | base64 -d
```

IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

# Bandit Level 12
```
cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'
```

5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

# Bandit Level 13
```
mkdir /tmp/folder
cp data.txt /tmp/folder
cd /tmp/folder
xxd -r data.txt > data
file data
mv data data.gz
gzip -d data.gz
file data
mv data data.bz2
bzip2 -d data.bz2
file data
mv data data.gz
gzip -d data.gz
mv data data.tar
tar xf data.tar
mv data5.bin data.tar
file data6.bin
mv data6.bin data.bz2
bzip2 -d data.bz2
mv data data.tar
tar xf data.tar
mv data8.bin data.gz
gzip data.gz
file data
cat data
```

8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
