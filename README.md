**Usage**
--
git pull this repo

`docker build -t telnet .`

`docker run -it telnet <host/ip> <optional port>`

**Exiting**
--
This image is using the built-in telnet functionality of busybox. Exiting is a little different after sending interrupt. ( CTRL + ] )
```
Console escape. Commands are:

 l	go to line mode
 c	go to character mode
 z	suspend telnet
 e	exit telnet
```
