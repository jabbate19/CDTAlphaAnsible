# CDT Team Alpha Ansible
## DO NOT RELEASE UNTIL AFTER COMPETITION

### This contains all of the ansible to configure all machines for competition.

## Deployment
To execute, run `ansible-playbook -i inventory/inventory.ini deploy.yml`

To only select a specific group, run `ansible-playbook -i inventory/inventory.ini -l windows deploy.yml` (Only windows systems used as example)

## To-Do List

- [x] Blue Team User
- [ ] AD
- [ ] DNS
- [x] Apache
- [ ] MySQL
- [ ] MongoDB
- [x] WinRM (Done manually to set up Ansible)
- [x] SSH ^^^
- [ ] RSync
- [x] IIS
- [x] Minecraft Docker
- [ ] SMB
- [x] SMTP
- [x] IMAP

