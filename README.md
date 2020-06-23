# GDB_CONF

Configure to disaasembly with Intel syntax and use gdb-peda configuration.

```
# mv gdbinit ~/.gdbinit

```
Only disassembly-flavor:

```
# echo "set disassembly-flavor intel" >> ~/.gdbinit
```

Only gdb-peda:

```
# echo "source ~/peda/peda.py" >> ~/.gdbinit
```

## More Information about gdb-peda:

PEDA - Python Exploit Development Assistance for GDB
Original Repository: <https://github.com/longld/peda>
