1. i logined into the Nautilus App Server 1

- then i ran the following  commands:
```sh
 ll /home/
 ```


```sh
cat /home/BSD.txt |grep software
```

```sh
sed '/\<software\>/d' /home/BSD.txt > /home/BSD_DELETE.txt
```


```sh
sed 's/\band\b/is/g' /home/BSD.txt > /home/BSD_REPLACE.txt
```
```sh
cat /home/BSD_REPLACE.txt |grep and
```

```sh
cat /home/BSD_REPLACE.txt |grep is
```