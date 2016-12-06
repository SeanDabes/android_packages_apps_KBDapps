# KBDapps
Here there are some apps thar are added by default to the ROM.

To include this apps, you have to add some lines to the file
`device/[vendor]/[model]/[model].mk`

The lines to add are:
`#KBDapps
PRODUCT_COPY_FILES += \
    packages/apps/KBDapps/KernelAdiutor.apk:system/priv-app/KernelAdiutor/KernelAdiutor.apk`
    
