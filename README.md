# OS---xv6-Multiuser-Project-

This file serves as a patch document illustrating the modifications and additions made to the existing xv6 code, transforming it from a single-user system to a multi-user environment. The key enhancements include:

1) Implementation of a login feature.
2) Addition of the adduser functionality.
3) Incorporation of addgroup capability.
4) Introduction of chmod command.
5) Integration of the switch user (SU) command.
6) Implementation of whoami command.
7) Introduction of id command.
8) Addition of getuid, getgid, and geteuid system calls.
9) Inclusion of setuid, setgid, and seteuid system calls.
10) Modification of ls -l command to display permissions.

To support these features, multiple system calls have been added, enhancing the overall functionality and transforming xv6 into a multi-user system.
