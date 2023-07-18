# Ansible
Structure d'un projet ansible
![image](https://github.com/borelsaffo/Ansible/assets/27947973/d6a75651-e656-4d71-b179-66c35642735d)

Explication de chaque élément :

inventories/ : Répertoire contenant les inventaires pour différents environnements tels que production et staging. Il contient également des fichiers de variables spécifiques aux groupes d'hôtes ou à tous les hôtes.
playbooks/ : Répertoire principal contenant les playbooks Ansible. Le fichier site.yml est généralement utilisé pour orchestrer l'exécution des rôles.
playbooks/roles/ : Répertoire contenant les rôles Ansible. Chaque rôle est un répertoire autonome contenant des tâches, des templates, des fichiers, etc., nécessaires à ce rôle spécifique.
library/ : Répertoire facultatif pour stocker les modules personnalisés que vous pouvez utiliser dans vos playbooks.
filter_plugins/ : Répertoire facultatif pour stocker les plugins de filtre personnalisés que vous pouvez utiliser dans vos playbooks.
vault.yml : Fichier contenant les variables sensibles chiffrées à l'aide de la fonctionnalité Ansible Vault.
ansible.cfg : Fichier de configuration d'Ansible contenant des paramètres tels que les chemins des inventaires, des rôles, etc.
README.md : Fichier contenant des informations sur le projet et son utilisation.
