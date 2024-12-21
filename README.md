# landscape-sysinfo

`landscape-sysinfo` provides an overview of various system metrics. It was developed as a Message of The Day (MoTD) script.

It has been tested on Debian 12.

It is powered by `bash` and a tiny bit of `awk` for floating-point arithmetic.

## Example output

```shell
Linux cloud 6.1.0-25-amd64 #1 SMP PREEMPT_DYNAMIC Debian 6.1.106-3 (2024-08-26) x86_64

  System information as of Sat Dec 21 13:07:56 CST 2024

  System load:               0.0
  Usage of /:                30% of 9.9G
  Memory usage:              25.6% of 480M
  Swap usage:                0%
  Processes:                 79
  Users logged in:           2
  IPv4 address for eth0:     1.2.3.4
  IPv4 address for docker0:  172.17.0.1

The uptime of this server is 4d 15h 7m.

Last login: Sat Dec 21 12:22:35 2024 from 1.2.3.4
```
