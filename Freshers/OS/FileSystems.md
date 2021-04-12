## Questions on filesystems

1. How to call the system functions like open, close
Why the functions are differentiated into kernel calls and userspace calls?
2. Why you can call a kernel function through user-space function (your own function) and why/how it doesn't violate the security principle of kernel?
3. Why userspace is preferred for an additional Filesystem over kernel (stability of kernel)?
4. Upcalls after reading a file, how are they generated, when are they generated
5. What are inodes, what are the attributes of an inode?
6. How the permissions on a file are managend in inodes?