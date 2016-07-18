************
Présentation 
************ 

Gp7 est une application de gestion académique développée en C# utilisant le `.NET Framework <http://en.wikipedia.org/wiki/.NET_Framework>`_ et `Microsoft SQL Server <http://en.wikipedia.org/wiki/Microsoft_SQL_Server>`_
. 

Gp7 est open source et publiée sous les termes de la `GNU General Public License v2 <http://www.gnu.org/licenses/gpl-3.0.en.html>`_
.

Philosophie
-----------

.. todo:: En cours de redaction


Fonctionnalités
---------------

Inscriptions (Etudiant et Scolarité)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Gère l'étudiant depuis son accès au système universitaire jusqu'à sa sortie en y laissant des traces à chaque niveau. Ce module contient :

- Les candidatures de nouveaux venus (Accès aux premières années) : Test d'admission et confirmation.
- Le passage en classe supérieure, redoublement / Affectation dans une autre classe de même niveau (ou inférieure)
- Immatriculation unique pour chaque étudiant
- Production de différentes cartes (comme la carte d’étudiant, de la bibliothèque,...)
- Gestion des démissions(abandon) et exclusions définitives
- Détection des étudiants frauduleux
- Production des rapports et statistiques

Études
^^^^^^
Gère les enseignants, les matières enseignées et les différentes classes d'une manière détaillée, il contient:

- Gestion complète de cours
- Le suivi d'avancement des programmes officiels (enseignants, modules, matières, chapitres, Périodes, jours, heures)
- Maîtriser les dossiers des enseignants (niveau d'études ou de formation, spécialité, Disponibilité,…)

Examens
^^^^^^^
Prend en charge les tests ou concours d'entrée, les devoirs de classe (travaux pratiques, travaux dirigés,...), les interrogations et les examens. Tout ceci allant de la gestion des candidatures aux résultats définitifs en passant par la saisie des notes. Et la production des bulletins de notes. Voici ce qui constitue ce module:

- Le paramétrage et l'uniformisation
- La saisie des notes par l'enseignant ou/et les secrétaires d'un jury
- La gestion des délibérations
- L'uniformisation des bulletins de notes
- L'établissement automatique des listes des candidats

Frais et paiements
^^^^^^^^^^^^^^^^^^
Prends en charge la gestion tous les différents frais académiques, entre autre les frais de différentes sessions, le frais d’enrôlements,…

- La création, la modification, la suppression d’un frais
- Vérifier, si l’étudiant est en ordre avec un frais ou non/ lister toutes les étudiants en ordre par classe (même chose pour les étudiants qui ne sont pas en ordre), affichage des étudiants en ordre avec les frais.
- Gestion de cas spéciaux pour chaque frais(Le cas des orphelins, Le cas des étudiants pris en charge par un professeur, une organisation, l’université, le cas d'une bourse).
- Affichage des frais par catégories selon les classes(promotions,départements, options,sections,...)
- Gestion de paiement par tranche pour des frais comme (le minerval).
- Élaboration des statistiques de paiement par classes pour une année.