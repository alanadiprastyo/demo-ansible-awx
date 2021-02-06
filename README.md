# demo-ansible-awx
Refrensi:
1. https://www.techsupportpk.com/2020/03/how-to-install-ansible-awx-centos-rhel-7-8.html
2. https://computingforgeeks.com/install-and-configure-ansible-awx-on-centos/
3. https://docs.ansible.com/ansible-tower/2.3.0/html/quickstart/
4. https://howto.lintel.in/install-ansible-tower-awx-centos-7/
5. https://www.ansible.com/blog/getting-started-writing-your-first-playbook

Awx CLI
```
awx login --conf.host http://192.168.122.110 --conf.username user --conf.password pass
awx --conf.token xxxxxxxxxxxxxxxxxxxx --conf.host http://192.168.122.110 user list
```
Format : {json,yaml,jq,human}
```
# awx --conf.token LXXXXXXXXXXXXXXXXXXXXXJ --conf.host http://192.168.122.110 users list -f human
id username 
== ======== 
6  aap      
4  adi      
1  admin    
3  alan     
5  pras
```
