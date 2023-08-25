# vnStat
Bastille template to install vnStat.

* Creates `/var/db/vnstat` with correct ownership and permissions.
* Installs vnStat.

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/vnstat
```

## Apply template
```
bastille template $JAIL jail-templates/vnstat
```

## Support
Templates will be maintained until their respective software version is end-of-life. Repositories will then be archived and removed from any meta-templates.

If you have a question, suggestion or find a bug, please let us know via an Issues in the relevant repository or send us an email.

## License
All templates are distributed under the 3-Clause BSD License. See `LICENSE` in every template repository for more information.
