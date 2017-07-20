# SSH Alias connector
Tool to short your access your favorite servers via ssh
Easy, written on bash.

# Installation
```bash
wget https://raw.githubusercontent.com/lokkie/ssh-alias-connector/master/fcon
chmod +x fcon
./fcon --install
```

# Adding new alias (connection)
```bash
➜  ~ fcon --add
Creating new connection
Type short name for connection:
example
Type short description for connection:
Connection to example com
Type connection host:
example.com
Type connection port [22]:

Type user (blank for default: lokkie):
superuser
Adding record [example:22:example.com:Connection to example com:superuser]
Done
```

# Using
```bash
fcon example
Connecting to example (Connection to example com)
	 [superuser@example.com:22]
Password:
```
