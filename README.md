# ansible-growi

underconstruction

Ansible playbook for GROWI on CentOS7

**GROWI Official site is https://docs.growi.org/**

**GROWI Official repository is https://github.com/weseek/growi**

ENVIRONMENT: CentOS7.5 1807 minimal install

USAGE: 

```
yum install -y ansible
git clone https://github.com/Naoria45/ansible-growi.git
cd ansible-growi.git
vim hosts  ## modify hosts file
## put public key to target server.
ansible-playbook -i hosts site.yml
```

After ansible-playbook ended, access the http://ipaddress:3000 with the browser.  
Then, you can find the account creation process.

The software versions I tested is below.

|  name  |  version  |
| ---- | ---- |
|  Node.js  | v8.11.4 |
|  MongoDB  | v3.6.7  |
|  yarn     | 1.9.4   |
|  Growi    | 3.2.2   |
|  ElasticSearch | 5.6.11 |

ATTENTION: This use MongoDB for database.  
Anyone can access MongoDB with **NO PASSWORD** by default setting.  
If you use this, DO SECURITY SETTING YOURSELF.


