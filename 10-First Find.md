#### Description

Unzip this archive and find the file named 'uber-secret.txt'

- [Download zip file](https://artifacts.picoctf.net/c/500/files.zip)

#Solucion1 
```
erkalexs-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/500/files.zip
erkalexs-picoctf@webshell:~$ unzip files.zip
erkalexs-picoctf@webshell:~$ grep -r "pico" files        
files/adequate_books/more_books/.secret/deeper_secrets/deepest_secrets/uber-secret.txt:picoCTF{f1nd_15_f457_ab443fd1}
```