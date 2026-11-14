recovery/root role
==================

In recovery trees recovery/root often is a directory from where all needed blobs are copied over.
For example, to make MTP work you will need init.recovery.usb.rc script and for recovery and needed services overall you would need init.recovery.qcom.rc where boot control hals, keymint etc.. are defined.
