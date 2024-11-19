Projet Ansible - Déploiement Automatisé de GitLab


Description
Ce projet a pour objectif d'automatiser le déploiement de GitLab et de PostgreSQL sur des machines virtuelles via Ansible. 

Prérequis
Machine de contrôle Ansible (peut être votre machine locale ou une VM dédiée)
Deux machines virtuelles : une pour GitLab et une pour la base de données PostgreSQL

Objectifs du projet
Déployer PostgreSQL sur une VM.
Installer et configurer GitLab sur une autre VM.
Automatiser toutes les étapes du déploiement, y compris l’installation des paquets nécessaires et la configuration des services.
Utiliser des rôles Ansible pour une gestion modulaire et réutilisable.


Reconfigurer GitLab : Pour reconfigurer GitLab après l'installation, vous pouvez utiliser la commande suivante :

gitlab-ctl reconfigure


Redémarrer PostgreSQL : Pour redémarrer le service PostgreSQL, utilisez :

sudo systemctl restart postgresql