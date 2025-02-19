#### Description

Can you make sense of this file?Download the file [here](https://artifacts.picoctf.net/c/475/enc_flag).

Hints:
Multiple decoding is always good.

#Solucion1 
```
erkalexs-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/475/enc_flag
erkalexs-picoctf@webshell:~$ cat enc_flag | base64 --decode | base64 --decode | base64 --decode | base64 --decode | base64 --decode | base64 --decode
picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_492767d2}
```