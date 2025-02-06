cs 153 - instructions to compile

**Clone the Repository:**  
```sh
https://github.com/ylian121/cs153_lab1.git
```

**Run with the commands:**    
```sh
make clean
make qemu-nox
```

-> goes into xv86
```sh
$
$ test
```

or

```sh
$
$ test_siblings
```
^^ directly type the test file name you want to test  

it will run

to exit qemu: control + A and then X

-> **be sure to exit qemu properly, otherwise it will continue running in the background**

gdb instructions for debugging
```sh
make qemu-nox-gdb
```

