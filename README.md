# CDT Team Alpha Ansible
## DO NOT RELEASE UNTIL AFTER COMPETITION

### This contains all of the ansible to configure all machines for competition.

## Deployment
To execute, run `ansible-playbook -i inventory/inventory.ini deploy.yml`

To only select a specific group, run `ansible-playbook -i inventory/inventory.ini -l windows deploy.yml` (Only windows systems used as example)

## To-Do List

- [x] Blue Team User
- [x] AD (MAYBE?)
- [x] DNS (MAYBE?)
- [x] Apache
- [x] MySQL
- [x] MongoDB
- [x] WinRM (Done manually to set up Ansible)
- [x] SSH ^^^
- [ ] RSync
- [x] IIS
- [x] Minecraft Docker
- [x] SMB (MAYBE?)
- [x] SMTP
- [x] IMAP

