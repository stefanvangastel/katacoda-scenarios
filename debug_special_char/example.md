Working example:

`docker container run -d debian:9 ping 127.0.0.1`{{execute}}

This does *not* work, looks the same though:

`docker container run –d debian:9 ping 127.0.0.1`{{execute}}

The difference is the dash `-` or MS Word dash `–` (`&#x2013`), which is actually a different char that corrupts input pasted into the terminal.