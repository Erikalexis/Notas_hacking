#### Description

Unzip this archive and find the flag.

- [Download zip file](https://artifacts.picoctf.net/c/503/big-zip-files.zip)

Hints:
Can grep be instructed to look at every file in a directory and its subdirectories?

#Solucion1 
```
erkalexs-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/503/big-zip-files.zip
erkalexs-picoctf@webshell:~$ unzip big-zip-files.zip
erkalexs-picoctf@webshell:~$ grep -r "pico" big-zip-files
big-zip-files/folder_pmbymkjcya/folder_cawigcwvgv/folder_ltdayfmktr/folder_fnpfclfyee/whzxrpivpqld.txt:information on the record will last a billion years. Genes and brains and books encode picoCTF{gr3p_15_m4g1c_ef8790dc}
```
