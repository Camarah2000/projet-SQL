Gestion des prêts de matériels pour un comité d’entreprise
🔹 Contexte
Dans le cadre d’un projet universitaire (INF403 - Gestion de données relationnelles et applications, UGA), nous avons conçu une base de données pour gérer le prêt de matériels aux employés d’un comité d’entreprise.

🔹 Objectifs du projet

Concevoir un modèle conceptuel UML (diagramme de classes) pour structurer les données.

Développer un diagramme d’objets UML illustrant des cas concrets d’emprunt.

Gérer les réservations et les prêts en tenant compte des contraintes (disponibilité, état des matériels, retards, etc.).

Assurer un suivi des emprunts par employé et par matériel.

🔹 Approche et outils

Outils utilisés : Draw.io, StarUML

Méthodologie : Conception UML, structuration des données, modélisation des relations

🔹 Résultat
Nous avons réalisé un modèle UML détaillé intégrant les relations entre employés, matériels, emprunts et réservations. Un diagramme d’objets illustre des scénarios concrets de prêts.

Parti2 ET FIN/
✅ Ce que nous avons fait
🔹 Question 1 : Modèle relationnel
Traduction du modèle UML fourni en un modèle relationnel complet.

Ajout des clés primaires (soulignées), des clés étrangères et contraintes.

Respect de la convention de nommage (attribut_Classe).

🔹 Question 2 : Script de création
Tous les DROP TABLE IF EXISTS, suivis des CREATE TABLE.

Contraintes d’intégrité (PRIMARY KEY, FOREIGN KEY, NOT NULL, etc.) incluses.

🔹 Question 3 : Transfert de données
Utilisation de requêtes INSERT INTO ... SELECT ... depuis la table fournie Resa.

Auto-incrémentation utilisée pour générer les identifiants manquants.

Ajout de notre propre structure d’arbre de catégories → sous-catégories → sous-sous-catégories.

🔹 Question 4 : Vues
Deux VIEW SQL :

Nombre d’emprunts en cours pour un employé

Nombre d’emprunts en cours pour chaque matériel

🔹 Question 5 : Requêtes SQL
Les 10 requêtes demandées sont présentes, numérotées et commentées.

Syntaxe claire et résultats testés sur notre base.

🔹 Compétences développées
✅ Modélisation UML (Diagramme de classes & d’objets)
✅ Conception de base de données relationnelle
✅ Gestion des contraintes métier et règles d’emprunt
✅ Travail collaboratif
