# Regex : A list of useful regex

- URL without ptotocol:
```
^(?=.{1,255}$)[0-9A-Za-z](?:(?:[0-9A-Za-z]|-){0,61}[0-9A-Za-z])?(?:\.[0-9A-Za-z](?:(?:[0-9A-Za-z]|-){0,61}[0-9A-Za-z])?)*\.?$
```

- IPv4 address:
```
(\b25[0-5]|\b2[0-4][0-9]|\b[01]?[0-9][0-9]?)(\.(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)){3}
```

- CVE reference:
```
CVE-\d{4}-\d{4,7}
```

- Duplicates:
```
^(.*)(\n\1)+$
```
