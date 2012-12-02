iops
====

A simple tool to benchmark block device IO operations.

Example
    ```

    $ sudo python -u iops -n 1 -b 4096 /dev/xvdb
    /dev/xvdb, 901.88 GB, device block size: 512  B, filesystem block size:   4 kB, 1 threads:
       4 KiB blocks: 1583.6 IO/s,   6.2 MiB/s ( 51.9 Mbit/s)
    ```
