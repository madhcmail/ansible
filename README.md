# ansible
contains ansible ad-hoc commands and playbooks
## ad-hoc Ansible commands
ansible [pattern] -m [module] -a "[module options]"

#### When are ad-hoc commands useful?
Ad-hoc commands are great for infrequent tasks. For example, if you need to restart a service across several hosts in response to an incident, you can quickly accomplish this with a one-liner.

Use cases for ad-hoc tasks:

Rebooting servers
Managing services
Managing files
Fact gathering
Connectivity testing
