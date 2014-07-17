######jak uruchomic gdb######
cc -g -std=c99 file1.c file2.c 

gdb:
gdb a.out
break filename:line_number
run c|n|s

######generating rsa key######
Generating SSH Keys
https://help.github.com/articles/generating-ssh-keys

python headers for the C code to compile:
$ sudo apt-get install python-dev
$ python setup.py build
$ workon crypto
$ python setup.py install
