# openssh-server-test

Run the command `make docker-compose-up` to start the server. After that, log into the server and try to connect to the clients

```
etorres@Helena:~/Development/openssh-server-test$ docker exec -it server bash
root@947090e4100d:/# ssh client1
Welcome to Ubuntu 20.04 LTS (GNU/Linux 5.4.0-37-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage


This system has been minimized by removing packages and content that are
not required on a system that users do not log into.

To restore this content, you can run the 'unminimize' command.
Last login: Thu Jun 25 04:10:00 2020 from 172.29.0.3
root@50fe4fe5cd2e:~#
```
