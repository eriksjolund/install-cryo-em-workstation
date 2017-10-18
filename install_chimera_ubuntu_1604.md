# Install Chimera on Ubuntu 16.04 as non-root user

1. Open the URL

https://www.cgl.ucsf.edu/chimera/download.html

in a web browser.

2. Click a download link for _Linux 64-bit_ (for instance https://www.cgl.ucsf.edu/chimera/cgi-bin/secure/chimera-get.py?file=linux_x86_64/chimera-1.12-linux_x86_64.bin
or https://www.cgl.ucsf.edu/chimera/cgi-bin/secure/chimera-get.py?file=linux_x86_64/chimera-1.11.2-linux_x86_64.bin )

3. Accept the license and download the file

5. Create an install directory where to install chimera 

(for instance _/tmp/chimera/1.11.2_ ).

Note _/tmp/_ is erased after reboots so you should probably choose something else.
Open up a terminal and type

```
user@laptop:~$ mkdir -p /tmp/chimera/1.11.2
```

6. Start the installation

``
user@laptop:~$ chmod 755 ~/Downloads/chimera-1.11.2-linux_x86_64.bin
user@laptop:~$ ~/Downloads/chimera-1.11.2-linux_x86_64.bin
```

7. Answer the question _Enter install location_

Type _/tmp/chimera/1.11.2_

7. Answer question _Install symbolic link to chimera executable for command line use in which directory?_

Type _0_


# Run Chimera


``
user@laptop:~$ /tmp/chimera-1.11.2/bin/chimera
```