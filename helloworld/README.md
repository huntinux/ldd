## How to play?
change KERNELDIR in Makefile to your local kernel tree path
then: 
```
make
sudo insmod hello.ko
```
you will see "Hello, world"

at last:
```
sudo rmmod hello
```
you will see "Goodbye, cruel world\n"
