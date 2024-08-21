# Passwords for the Century game - [Game here](https://underthewire.tech/century)
## Level 1 > 2
**:computer:Command:**

```sh
$psversiontable (to see build version. Then go to the line with Name)
```

**:unlock:Password:**

```sh
10.0.14393.7254
```

## Level 2 > 3
**:computer:Command:**

```sh
(It appears wget is an alias for invoke-webrequest, so the first part of our password is invoke-webrequest. Now we only need to add the name of the file on the desktop)
ls
(We see a file named "443")
```

**:unlock:Password:**

```sh
invoke-webrequest443
```
## Level 3 > 4
**:computer:Command:**

```sh
(get-childitem -path c:\users\century3\desktop -file).count
```

**:unlock:Password:**

```sh
123
```

## Level 4 > 5
**:computer:Command:**

```sh
ls
cd "Can You Open Me"
```

**:unlock:Password:**

```sh
34182
```

## Level 5 > 6
**:computer:Command:**

```sh
(First half of the password)
get-addomain
(The name is "underthewire")
(Second half of the password)
ls
```

**:unlock:Password:**

```sh
underthewire3347
```

## Level 6 > 7
**:computer:Command:**

```sh
(Similar to 3 > 4)
(Get-ChildItem -Path "C:\Users\century3\Desktop" -Directory).Count
```

**:unlock:Password:**

```sh
197
```
## Level 7 > 8
**:computer:Command:**

```sh
see later
```

**:unlock:Password:**

```sh
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

## Level 8 > 9
**:computer:Command:**

```sh
ls
(There's only one file named "unique.txt"
get-content unique.txt
(We get a bunch of words - let's sort them and count them)
get-content unique.txt | sort-object -unique | measure-object
```

**:unlock:Password:**

```sh
696
```

## Level 9 > 10
**:computer:Command:**

```sh
cat readme
```

**:unlock:Password:**

```sh
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

## Level 10 > 11
**:computer:Command:**

```sh
cat < - 
```

**:unlock:Password:**

```sh
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```
## Level 11 > 12
**:computer:Command:**

```sh
cat readme
```

**:unlock:Password:**

```sh
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

## Level 12 > 13
**:computer:Command:**

```sh
cat < - 
```

**:unlock:Password:**

```sh
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

## Level 13 > 14
**:computer:Command:**

```sh
cat < - 
```

**:unlock:Password:**

```sh
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

## Level 14 > 15
**:computer:Command:**

```sh
cat < - 
```

**:unlock:Password:**

```sh
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```
