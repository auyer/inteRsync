# IDEA: Interactive rsync

Using librsync,

- Select line and sync from origin to destination.
- connect to rsyncd for faster checking

| Source    | Destination               |
|---------- |-------------------------- |
| folder/x (modified dd/mm/yyyy) | folder/x (up to date)     |
| folder/y (modified dd/mm/yyyy) | ~folder/y~ (not present)  |
| folder/z (modified dd/mm/yyyy) | folder/z (need update)    |
