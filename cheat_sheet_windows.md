# Cheat Sheet Windows (Raccourcis & Commandes)

> **Note technique :** `DWORD` = 4 octets = 32 bits. Par conséquent, de nombreux dossiers et clés système Windows historiques restent configurés ou nommés en référence au 32 bits, même sur des architectures modernes en 64 bits.

---

## Raccourcis Clavier Windows (Win + ...)

| Raccourci | Action |
| :--- | :--- |
| **Win + D** | Afficher ou masquer le bureau |
| **Win + E** | Ouvrir l'Explorateur de fichiers |
| **Win + I** | Ouvrir les Paramètres Windows |
| **Win + R** | Ouvrir la boîte de dialogue « Exécuter » |
| **Win + L** | Verrouiller l'ordinateur |
| **Win + S** (ou **Win + Q**) | Ouvrir la recherche Windows |
| **Win + Tab** | Ouvrir la Vue des tâches (*Task View*) / Basculer entre les bureaux |
| **Win + Flèche Gauche / Droite** | Ancrer la fenêtre active sur le côté gauche ou droit de l'écran |
| **Win + Flèche Haut / Bas** | Agrandir / Réduire ou masquer la fenêtre active |
| **Win + Point (.)** ou **(;)** | Ouvrir le panneau des émojis et symboles |
| **Win + Impression écran** | Faire une capture d'écran complète et l'enregistrer dans *Images* |
| **Win + A** | Ouvrir les Paramètres rapides et le Centre de notifications |
| **Win + X** | Ouvrir le menu des liens rapides (Menu système avancé) |
| **Win + V** | Ouvrir l'historique du Presse-papiers |
| **Win + P** | Choisir un mode d'affichage multi-écrans / projections |
| **Win + C** | Lancer l'assistant Microsoft Copilot |
| **Win + M** | Réduire toutes les fenêtres |
| **Win + Maj + M** | Restaurer les fenêtres réduites via Win + M |
| **Win + Z** | Ouvrir les dispositions d'ancrage (*Snap Layouts*) |
| **Win + Ctrl + D** | Créer un nouveau bureau virtuel |
| **Win + Ctrl + Flèche G / D** | Naviguer d'un bureau virtuel à l'autre |
| **Win + Ctrl + F4** | Fermer le bureau virtuel actif |
| **Win + Début (Home)** | Réduire toutes les fenêtres, sauf la fenêtre active |
| **Win + Maj + S** | Lancer l'outil Capture d'écran (zone précise) |
| **Win + G** | Ouvrir la Xbox Game Bar (performances, captures vidéo) |
| **Win + Alt + R** | Démarrer ou arrêter l'enregistrement vidéo de l'écran |
| **Win + H** | Activer la dictée vocale (saisie de texte par la voix) |
| **Win + K** | Ouvrir le menu de connexion sans fil (*Cast*) |
| **Win + W** | Ouvrir le volet des Widgets |
| **Win + U** | Ouvrir le centre d'Accessibilité (options d'ergonomie) |
| **Win + Plus (+)** / **Moins (-)**| Activer la Loupe Windows et zoomer / dézoomer |

### Autre raccourci utile
* **Alt + D** : Sélectionner et copier l'URL dans un navigateur ou le chemin d'accès dans l'Explorateur de fichiers.

---

## Consoles de gestion Microsoft (.MSC)
*Ces commandes s'exécutent avec la boîte de dialogue **Win + R**.*

| Commande | Nom de la console | Description / Utilité |
| :--- | :--- | :--- |
| **devmgmt.msc** | Gestionnaire de périphériques | Gérer les pilotes, composants matériels et ressources |
| **compmgmt.msc** | Gestion de l'ordinateur | Regroupe la gestion des disques, services, événements, etc. |
| **services.msc** | Services Windows | Démarrer, arrêter et configurer les services d'arrière-plan |
| **diskmgmt.msc** | Gestion des disques | Partitionner, formater et gérer les volumes de stockage |
| **eventvwr.msc** | Observateur d'événements | Consulter les journaux système, de sécurité et d'applications |
| **taskschd.msc** | Planificateur de tâches | Planifier le lancement automatique de scripts ou programmes |
| **secpol.msc** | Stratégie de sécurité locale | Configurer les droits d'accès et règles de sécurité locales |
| **gpedit.msc** | Éditeur de stratégie de groupe | Configuration avancée du système (*Éditions Pro/Entreprise*) |
| **lusrmgr.msc** | Utilisateurs et groupes locaux | Gérer les comptes utilisateurs et groupes de la machine |
| **perfmon.msc** | Moniteur de performances | Analyser l'utilisation du processeur, de la RAM et du réseau |
| **fsmgmt.msc** | Dossiers partagés | Visualiser et gérer les partages réseau actifs et sessions |

---

## Panneaux de configuration (.CPL)
*Ces commandes permettent d'accéder directement aux anciens ou nouveaux modules du panneau de configuration.*

| Commande | Module cible | Description / Utilité |
| :--- | :--- | :--- |
| **ncpa.cpl** | Connexions réseau | Configurer les cartes réseau (Wi-Fi, Ethernet, IP, DNS) |
| **appwiz.cpl** | Programmes et fonctionnalités | Désinstaller ou modifier des applications et fonctionnalités |
| **sysdm.cpl** | Propriétés système | Modifier le nom du PC, le domaine, les variables d'environnement |
| **main.cpl** | Propriétés de la souris | Configurer le curseur, la vitesse et les boutons de la souris |
| **desk.cpl** | Paramètres d'affichage | Ajuster la résolution, l'orientation et la disposition des écrans |
| **mmsys.cpl** | Paramètres Son | Gérer les périphériques de lecture, d'enregistrement et sons système |
| **firewall.cpl** | Pare-feu Windows Defender | Configurer les règles de trafic réseau et blocages |
| **powercfg.cpl** | Options d'alimentation | Choisir ou modifier les modes de gestion de l'énergie |
| **intl.cpl** | Région | Modifier le format de la date, de l'heure et des nombres |
| **timedate.cpl** | Date et heure | Régler l'horloge système et les fuseaux horaires |
| **hdwwiz.cpl** | Assistant Ajout de matériel | Forcer l'installation d'un périphérique non détecté |

---

## Utilitaires Système et Commandes CLI Fondamentales
*Commandes universelles pour le diagnostic et la configuration (à taper dans **Win + R**, **CMD**, ou **PowerShell**).*

| Commande | Type / Outil | Description / Utilité |
| :--- | :--- | :--- |
| **msinfo32** | Utilitaire Système | Informations système complètes (matériel, composants, OS) |
| **regedit** | Utilitaire Système | Éditeur du Registre Windows (gestion des ruches et clés) |
| **taskmgr** | Utilitaire Système | Gestionnaire des tâches (processus, performances, démarrage) |
| **cmd** | CLI | Ouvrir l'invite de commandes classique |
| **powershell** | CLI | Ouvrir la console d'automatisation PowerShell |
| **wt** | CLI | Ouvrir Windows Terminal (si installé) |
| **ipconfig /all** | Commande CLI | Afficher la configuration IP complète de toutes les cartes |
| **ping [adresse]** | Commande CLI | Tester la connectivité réseau vers un hôte ou un site |
| **sfc /scannow** | Commande CLI | Vérifier et réparer l'intégrité des fichiers système (*Admin*) |
| **chkdsk /f** | Commande CLI | Analyser et réparer les erreurs sur le disque dur (*Admin*) |
| **netstat -ano** | Commande CLI | Lister toutes les connexions réseau actives et leurs ports/PID |
