# mycmd
my bash command

# List

- ymd
- bkup
- sshconfp

## ymd

print `%Y%m%d` or create some format file named `%Y%m%d`

### Usage

```
ymd [-d] [-m] [-t] [-h]
-d    make %Y%m%d directory
-m    make %Y%m%d markdown file
-t    make %Y%m%d txt file
-h    print help
```

## bkup

create buckup file  
default format is `TARGET_FILE_NAME_%Y%m%d%H%M%S`

### Usage

```
bkup [-h]
-h    print help
```

### TODO

- [ ] set backup format

### sshconfp

print ssh config file

### Usage

```
$ sshconfp
     1	Host *
     2	  UseKeychain yes
     3
     4	Include */config
     1	Host aount1.github
     2	    HostName        github.com
     3	    IdentityFile    ~/.ssh/github/aount1.github
     4	    IdentitiesOnly  yes
     5	Host aount2.github
     6	  User git
     7	  Port 22
     8	  HostName bitbucket.org
     9	  IdentityFile ~/.ssh/github/aount2.github
    10	  TCPKeepAlive yes
    11	  IdentitiesOnly yes
    12
```
