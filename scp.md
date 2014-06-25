scp - secure copy (remote file copy program)
============================================
Moving a file between servers where your local machine can talk to both 
machines but the two machines cannot talk to each other you can pass in the
`-3` flag. The description for that flag is as follows:

>   -3      Copies between two remote hosts are transferred through the local
>           host.  Without this option the data is copied directly between the
>           two remote hosts.  Note that this option disables the progress meter.
