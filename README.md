# systemcallOS
this project about system call in pintos 

Step1: you must modify  pintos,pintos.pm and gdb in scr/utils which will help your OS find your kenel and debug it.

Step2: in src/userprog ,run 'make '

Step3:cd build and run 'pintos-mkdisk filesys.dsk --filesys-size=2' that will create  a disk with a file system partion which is very important in this project.

Step4 :run ' pintos -f -q'.

Step 5: run 'make' in src/example

Step 6: run 'pintos -p ../../examples/echo -a echo -- -q' ( replace by link of echo.c)

Step 7:pintos -q run 'echo x'

Step 8 : run ' make check ' and waiting for this process,get the result of test cases


