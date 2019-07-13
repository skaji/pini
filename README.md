# pini

Tiny `init` for containers.

# Usage

```
FROM ubuntu
ADD https://github.com/skaji/pini/raw/master/pini /sbin/pini
RUN chmod +x /sbin/pini
ENTRYPOINT ["/sbin/pini", "--"]
```

# Author

Shoichi Kaji

# License

MIT
