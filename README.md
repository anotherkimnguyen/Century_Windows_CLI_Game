# Passwords for the Century game - [Game here](https://underthewire.tech/century)
## Level 1 > 2
**Command:**

```sh
$psversiontable
```

**Password:**

```sh
10.0.14393.7254
```

## Level 2 > 3
**Command:**

```sh
ls
```

**Password:**

```sh
invoke-webrequest443
```
## Level 3 > 4
**Command:**

```sh
(get-childitem -path c:\users\century3\desktop -file).count
```

**Password:**

```sh
123
```

## Level 4 > 5
**Command:**

```sh
ls
cd "Can You Open Me"
ls
```

**Password:**

```sh
34182
```

## Level 5 > 6
**Command:**

```sh
get-addomain
ls
```

**Password:**

```sh
underthewire3347
```

## Level 6 > 7
**Command:**

```sh
(Get-ChildItem -Path "C:\Users\century6\Desktop" -Directory).Count
```

**Password:**

```sh
197
```
## Level 7 > 8
**Command:**

```sh
set-location c:\users\century7
ls
get-childitem .\ -include *readme* -recurse
get-content .\Downloads\Readme.txt
```

**Password:**

```sh
7points
```

## Level 8 > 9
**Command:**

```sh
ls
get-content unique.txt
get-content unique.txt | sort-object -unique | measure-object
```

**Password:**

```sh
696
```

## Level 9 > 10
**Command:**

```sh
ls
get-content Word_File.txt
get-content Word_File.txt -Delimiter ‘ ‘
get-content Word_file.txt -Delimiter ' ' | select-object -index 160
```

**Password:**

```sh
pierid
```

## Level 10 > 11
**Command:**

```sh
get-wmiobject win32_service | where-object {$_.Name -eq 'wuauserv'} | select-object description
ls
```

**Password:**

```sh
windowsupdates110
```
## Level 11 > 12
**Command:**

```sh
set-location c:\users\century11
dir -force .\Downloads 
```

**Password:**

```sh
secret_sauce
```

## Level 12 > 13
**Command:**

```sh
get-addomaincontroller
get-adcomputer -properties description -filter 'Name -like "UTW"’
ls 
```

**Password:**

```sh
i_authenticate_things 
```

## Level 13 > 14
**Command:**

```sh
get-content countmywords -delimiter ' ' | measure-object -word
```

**Password:**

```sh
755
```

## Level 14 > 15
**Command:**

```sh
ls
get-content countpolos
get-content countpolos | select-string -pattern "polo" -allmatches | measure-object -word
```

**Password:**

```sh
19482
```
