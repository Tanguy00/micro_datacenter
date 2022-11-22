Projet d'ASSE à l'UPJV, Master Informatique.<br />
*Le DC est constitué d'un mini ordinateur (Shuttle) et de trois Raspberry PI.*

:warning: **Pré-requis sur le Shuttle :** accès physique avec écran et clavier, Python et Git installé.
<br /><br />

## Installation d'Ansible
```bash
python -m venv .pyenv
source .pyenv/bin/activate  # On entre dans l'env

python3 -m pip install ansible==6.6

deactivate               # On sort de l'env

ansible --version
```
<br />

## Déploiement Ansible

