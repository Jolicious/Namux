# Namux 

## The "Namux" script simplifies the setup of a productive environment within a Tmux session. It's designed for providing easy access to essential tools which are Firefox, a Work Panel, and Burp Suite in one command.

### Edit the script as prefered and adjust the path of the vpn or the number of vpns.

Download it using git

```bash
git clone https://github.com/Jolicious/Namux.git
```

Give executable permission
```bash
chmod +x namux
```

Move the file to `/usr/local/bin/`
```bash
mv namux /usr/local/bin/
```

Usage:
Without VPN:
```bash
namux
```

With VPN:
```bash
namux vpn1
```
or
```bash
namux vpn2
```

