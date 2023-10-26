# Remote development over SSH

## Install the extension

Remote - SSH

# local

```sh
ssh-keygen -t ed25519
```

# remote host

copy public key into remote host home directory .ssh/

# point to private key

command pallet (F1) or (CMD + Shift + P)
Remote-SSh: Open SSH Configuration File...
/Users/james/.ssh/config

```text
Host name-of-remote-host
 HostName xxx.xxx.xxx.xxx
 User user-name-on-remote-host
 IdentityAgent ~/.ssh/name-of-private-key
```

