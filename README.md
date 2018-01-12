# mycmd
my bash command

# List

- ymd
- bkup

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
