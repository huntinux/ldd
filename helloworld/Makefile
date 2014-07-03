
KERNELDIR = /home/hongjin.cao/work/kernel/linux-2.6.32.63



modules:
	$(MAKE) -C $(KERNELDIR) M=`pwd` modules

modules_install:
	$(MAKE) -C $(KERNELDIR) M=`pwd` modules_install

clean:
	rm -rf *.o *~ core .depend .*.cmd *.ko *.mod.c .tmp_versions

.PHONY: modules modules_install clean


obj-m := hello.o
