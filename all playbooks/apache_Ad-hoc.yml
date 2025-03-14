To install
```bash
ansible all -m yum -a "name=httpd state=present" -b
```


To start
```bash
ansible all -m service -a "name=httpd state=started enabled=true" -b
```

To stop
```bash
ansible all -m service -a "name=httpd state=stopped enabled=true" -b
```

To remove
```bash
ansible all -m service -a "name=httpd state=stopped enabled=no" -b
ansible all -m yum -a "name=httpd state=absent" -b
```
