# TODO CHANGE THIS TO USE $(CONFIG_VIDEO_ARDUCAM)
# https://www.kernel.org/doc/Documentation/kbuild/makefiles.txt
obj-m	+= arducam.o

modules:
	$(MAKE) -C '$(LINUX_DIR)' M='$(PWD)' modules