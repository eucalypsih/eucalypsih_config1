```bash
git clone -q git@github.com:eucalypsih/eucalypsih_config1.git && cd eucalypsih_config1 && git config user.name "eucalypsih" && git config user.email "eucalypsih@gmail.com" && git branch -M main && git pull origin main --allow-unrelated-histories

```

[How to Search Strings in Binary Files](https://linuxopsys.com/search-strings-in-binary-files)
```bash
hexdump -e '/1 "%02X"' /usr/bin/nproc | grep 68656C70

```
