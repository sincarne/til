To create a user:
```
adduser <username>
```
To add a user to `sudoers`:
```
adduser <username> sudo
```
To create a user's home directory and copy `/etc/skel`:
```
mkhomedir_helper <username>
```
To change another user's password:
```
passwd <username>
```
To delete a user and their group, if they're the only member:
```
deluser <username>
```
