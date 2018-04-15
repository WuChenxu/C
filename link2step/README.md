a demo to show how to link a project w/ files which have same name and functions have same name

it is tested in Macbook Pro.
for the linux enviroment, the command `ld -r -exported_symbols_list exported_sym.list ${OBJECTS}  -o ${TARGET}.o` should be checked,
`-exported_symbols_list` should be replaced by `--retain-symbols-file`.

check also in my blog:
[link same name functions](https://wuchenxu.com/2018/04/15/integrate-files-with-same-name-same-function-in-C/)

```
make clean
make
```
