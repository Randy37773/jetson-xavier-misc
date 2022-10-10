# jetson-xavier-misc
problems, solutions, logs while trying to tame jetson-xavier

* in order to increas usb-buffer-size to max:

     $sudo su

     $ crontab -e

     insert this

     @reboot echo 0 > /sys/module/usbcore/parameters/usbfs_memory_mb

