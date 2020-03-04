# vanilluxe
Website and scripts for Vanilluxe

### Files

* `backup` Automated backup script, backups are served from the website
* `vanilluxe-th3-z-xyz` Public website sources
* `vanilluxe-th3-z-xyz.conf` Nginx config for public website, proxy for dynmap

#### Crontab

'''
0 0 * * * /srv/minecraft-vanilluxe/backup
0 6 * * * /srv/minecraft-vanilluxe/backup
0 12 * * * /srv/minecraft-vanilluxe/backup
0 18 * * * /srv/minecraft-vanilluxe/backup
'''
