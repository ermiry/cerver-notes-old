# Sockets

## What is a socket?

**How sockets are implemented in the LINUX OS?**
A socket is an abstraction of a communication endpoint. Just as they would use file
descriptors to access files, applications use socket descriptors to access sockets. Socket
descriptors are implemented as file descriptors in the UNIX System. Indeed, many of
the functions that deal with file descriptors, such as read and write, will work with a
socket descriptor.

**Maybe some sockets configuration?**