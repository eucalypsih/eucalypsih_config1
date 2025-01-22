[How to Search Strings in Binary Files](https://linuxopsys.com/search-strings-in-binary-files)
```bash
hexdump -e '/1 "%02X"' /usr/bin/nproc | grep 68656C70

```
