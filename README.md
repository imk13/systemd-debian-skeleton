Debian packaging with systemd

https://bunn.cc/2017/debian-packaging-with-systemd/

Run following commands to build debian binary with project files in usr/share directory.

- ``` cd systemd-demo```
- ```dpkg-buildpackage -rfakeroot -uc -us```

Credits:
- https://askubuntu.com/a/674054/1636841
- https://unix.stackexchange.com/a/627703/516544
