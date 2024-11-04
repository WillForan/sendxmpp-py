# sendxmpp-py

`sendxmpp` is the XMPP equivalent of sendmail. It is an alternative to the old sendxmpp written in Perl.

## Install
with `pipx` like

```
pipx install git+https://github.com/WillForan/sendxmpp-py
```


## Configuration
See the example [sendxmpp.cfg](./sendxmpp.cfg).

`cp sendxmpp.cfg ~/.config/` and edit `~/.config/sendxmpp.cfg` with your XMPP credentials

```
[sendxmpp]
jid = username@example.net
password = qwerty
```

## Usage examples

- `echo "This is a test" | sendxmpp user@host`
- `sendxmpp user@host <README.md`

License
-------
GNU/GPLv3 - Check LICENSE.md for details
