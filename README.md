# mycmd
my bash command

# List

- ymd
- bkup
- sshconfp
- heic2jpg

## ymd

print `%Y%m%d` or create some format file named `%Y%m%d`

### Usage

```
ymd [-f] [-d] [-m] [-t] [-h]
-f [h, m, s]  setting print time format
-d            make %Y%m%d directory
-m            make %Y%m%d markdown file
-t            make %Y%m%d txt file
-h            print help
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

## sshconfp

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

## heic2jpg

convert heic to jpg for recursion

### Usage

```bash
cd TARGET_DIR
heic2jpg
```
