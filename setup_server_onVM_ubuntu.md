### Completely remove package:
```bash 
sudo apt purge <package_name> 
```
### search all packages have name like "key_word":
```bash
sudo dpkg -l *key_word* 
```
### Cannot install mysqlclient by pip3
```bash
sudo apt-get install python-dev default-libmysqlclient-dev
sudo apt-get install python3-dev
pip install mysqlclient
```
