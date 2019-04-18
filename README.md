# Tabline
This VIM plugin provides a simple, minimal, black-and-white "tabline" with some handy features. The tabline will look something like the following:

```
··· 2|name2.ext  3|·ry_long_name.e·  4|name4.ext ···
```

The directory name is omitted from tab name. If the file name is more than 12 characters
long, the beginning and end of the name are truncated and replaced with `·` characters.
If there are two many tabs open for the window width, the leading and trailing tabs
surrounding the current tab are truncated and replaced with `···`.  See the source code for details.


