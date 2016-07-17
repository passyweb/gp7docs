************
Installation
************

Configuration système
---------------------

Gp7 utilise un environnement de domaine Windows et les utilisateurs proviennent d’un AD (Active Directory).

Pour un meilleur fonctionnement, Gp7 nécessite une configuration système minimale tant logicielle que matérielle.

**Configuration logicielle minimale requise :**

- Systèmes d’exploitation pris en charge : Windows 7, Windows Server 2008 R2, Windows Server 2008 Service Pack 1
- Active Directory dans un domaine Windows 2008 pour les utilisateurs et les ordinateurs
- Microsoft SQL Server 2008
- `.Net Framework 4.5 <https://www.microsoft.com/fr-fr/download/details.aspx?id=30653>`_ : 
    - Windows 10 est livré avec .NET Framework 4.6 préinstallé : l'installation de ce package n'est donc pas nécessaire. Ce package n'est pas applicable pour Windows 10 et ne peut pas être installé sur ce système.
- `Microsoft Report Viewer 2012 Runtime <https://www.microsoft.com/fr-fr/download/details.aspx?id=35747>`_ : 
    - Composant requis : Le package Types CLR du système SQL Server: `x86 <http://go.microsoft.com/fwlink/?LinkID=239643&clcid=0x409>`_ ou `x64 <http://go.microsoft.com/fwlink/?LinkID=239644&clcid=0x409>`_


**Configuration matérielle minimale requise :**

- Postes clients
    - Processeur 1 GHz minimum
    - 512 Mo de mémoire vive (RAM)
    - 850 Mo d'espace disque disponible (x86)
    - Disque dur 2 Go (x64)
- Windows Server 2008 : Plus de détails sur ce `lien <https://technet.microsoft.com/en-us/library/ef8f3711-d1d1-4d4a-8a04-ee7bf6110554>`_

- Microsoft SQL Server 2008 : Pour de détails sur ce `lien <https://msdn.microsoft.com/en-us/library/ms143506(v=sql.100).aspx>`_

Obtenir Gp7
-----------

Gp7 est disponible gratuitement sur sur la `forge <https://forge.umons.ac.be>`_  de l'`Université de Mons <http://www.umons.ac.be>`_

Processus d'installation
------------------------


Installation et configuration du domaine
""""""""""""""""""""""""""""""""""""""""

Plus de détails `ici <http://www.howtogeek.com/99323/installing-active-directory-on-server-2008-r2/>`_


Installation et configuration du serveur de base de données
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""

Plus de détails `ici <http://blog.sqlauthority.com/2008/06/12/sql-server-2008-step-by-step-installation-guide-with-images/>`_
et `là <http://www.sqlservercentral.com/articles/SQL+Server+2008/74856/>`_


Installation de Gp7 sur les postes clients
""""""""""""""""""""""""""""""""""""""""""

Double-cliquez sur le fichier d'installation téléchargé depuis la forge

    .. image:: images/install_1.png
        :scale: 60%
        :align: center

Suivez les différentes étapes d'installation

    .. image:: images/install_2.PNG
        :scale: 60%
        :align: center

 Licence   
    .. image:: images/install_3.png
        :scale: 60%
        :align: center

 Dossier d'installation  
    .. image:: images/install_4.png
        :scale: 60%
        :align: center

 Dossier du menu Démarrer    
    .. image:: images\install_5.PNG
        :scale: 60%
        :align: center

 Prêt à installer   
    .. image:: images\install_6.PNG
        :scale: 60%
        :align: center

 Installation en cours    
    .. image:: images\install_7.PNG
        :scale: 60%
        :align: center