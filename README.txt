General Information
===================

Linux driver for Realtek PCI-Express card reader chip.


Build Steps
===========

1) make
2) make install
3) depmod -a
4) echo blacklist rtsx_pci_sdmmc >>/etc/modprobe.d/blacklist.conf
5) update-initramfs -u
6) reboot your computer

Note: Root privilege is required in step 2, 3, 4 and 5
