This is a collection of small utilities and wrappers for termux on Android.


    ssh

Wrapper for ssh to add simple hosts file support.


Can be symlinked to scp as well as ping (symlinked as "zing" by default). Wrapper selects function based on arg0.


Checks for hosts file at location "/data/data/com.termux/files/home/.ssh/ssh_hosts".




Note: only the most basic hosts file functionality is supported. For example, "123.45.678.90    somehost" will work. "123.45.678.90    somehost.localdomain somehost" will not. Only spaces are supported, no tabs.
