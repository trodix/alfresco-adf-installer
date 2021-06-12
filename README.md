# Script d'installation alfresco-adf

## Prérequis

- Avoir installé Ansible sur le pc depuis lequel on lance ce script
- Avoir copié sa clé ssh sur tous les servers listés dans hosts.yml via
  `ssh-copy-id user@server`

## Installation

Lancer la commande suivante:

```bash
ansible-playbook -i hosts.yml --user=user playbook.yml
```
