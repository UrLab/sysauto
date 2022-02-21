# Ansible is love

pour executer : (avec une clef SSH pour se log in)
```
ansible-playbook -K <playbook_fil_name.yml>
```

# Utilité :
Initialement utilisé pour déployer des users IRC facilement, peut être utilisé pour de la maintenance générale
(en ajouttant les machines dans le fichier host)

# Dépendances :
```
git pull --recurse-submodules
git submodule update --init --recursive
```
