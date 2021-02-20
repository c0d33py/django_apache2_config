# django_apache2_config


**Apache2 server configrations for private linux servers**

`$ sudo apt-get install apache2`

`$ sudo apt-get install libapache2-mod-wsgi-py3`

`$ cd /etc/apache2/sites-available/`

`$ ls`

`$ sudo cp 000-default.conf django_apache2_enable.conf`

`$ sudo a2enmod wsgi`

**add inside wsgi.py**

```
import sys

sys.path.append('/home/YOURNAME/PROJECT/server')
```
