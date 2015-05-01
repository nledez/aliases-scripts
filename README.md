Installation
============

```bash
sudo cp mail_alias_add mail_alias_search /usr/local/bin/
```

Add aliases at the end of /etc/aliases.

Replace "nico" by your local user.

Use
===

To add a site:
```bash
mail_alias_search site.com
# Show all entries contains site.com
# Or if missing:
# Open a vi editor on /etc/aliases
/NEW
# To search mark
yyP
# To clone the current line and stay on the upper line
ccw
# To replace the "NEW" mark with the aliases of your choice
ESC
:wq
# To save update it launch automaticaly aliases update
```
