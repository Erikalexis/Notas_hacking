## Description

Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/94d00153b0057d37da225ee79a846c62/strings) without running it?

#Solucion1 
```
erkalexs-picoctf@webshell:~$ wget https://jupiter.challenges.picoctf.org/static/94d00153b0057d37da225ee79a846c62/strings
erkalexs-picoctf@webshell:~$ strings strings | grep picoCTF
picoCTF{5tRIng5_1T_d66c7bb7}
```