This is a simple hello world driver written in c for linux.

## How to Run
1. compile by running `make`
2. run command `sudo insmod main.ko`
3. run `lsmod|grep main` to check if it is loaded
4. run `dmesg|tail -1` to view printed hello world message
5. run `make clean` to remove generated files
6. run `remod main` to remove the driver