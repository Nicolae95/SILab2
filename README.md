# SILab2
Denial-of-service (DoS) attacks typically flood servers, systems or networks with traffic in order to overwhelm the victim resources 
and make it difficult or impossible for legitimate users to use them. 
While an attack that crashes a server can often be dealt with successfully by simply rebooting the system,
flooding attacks can be more difficult to recover from.

In my laboratory work I've used both and an OWASP tool and my self made script for a slowloris attack.
As a server I've used an Apache2 web server and tested it on localhost.
During the analysis I've noticed that the server stops it's work at 450 sockets. 
If we use less then it still works but really slow
