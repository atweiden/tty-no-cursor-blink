Turns off tty cursor blinking.


Usage
-----

### runit

```sh
cp -R runit/tty-no-cursor-blink /etc/sv
ln -s /etc/sv/tty-no-cursor-blink /var/service
```

### systemd

```sh
cp systemd/tty-no-cursor-blink.conf /etc/tmpfiles.d
```


Licensing
---------

This is free and unencumbered public domain software. For more
information, see http://unlicense.org/ or the accompanying UNLICENSE file.
