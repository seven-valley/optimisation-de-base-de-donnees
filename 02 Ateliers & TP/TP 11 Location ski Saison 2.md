# TP 11 - Ski Saison 2

Intégrer ces jeux d'essaies supplementaires  
- Attention ils sont en SQL Server de microsoft  
- Vous devez les convertir si besoin  
- Vous pouvez utiliser chat GPT  

```sql
INSERT Clients VALUES(20, 'Dubosc', 'Frank', '12 avenue des flots bleus', '76140', 'Petit-Quevilly');
INSERT Clients VALUES(21, 'Boon', 'Dany', '22 rue des Ch''tis', '59280', 'Armentières');
INSERT Clients VALUES(22, 'Elmaleh', 'Gad', '45 rue du sentier', '75001', 'Paris');
INSERT Clients VALUES(23, 'Dujardin', 'Jean', 'rue Brice', '92500', 'Rueil-Malmaison');
INSERT Clients VALUES(24, 'Marceau', 'Sophie', 'Boulevard de la Boom', '75010', 'Paris');
INSERT Clients VALUES(25, 'Merad', 'Kad', 'Rue du petit nicolas', '91130', 'Ris-Orangis');
INSERT Clients VALUES(26, 'Seigner', 'Mathilde', '357 rue du Camping', '75012', 'Paris');
INSERT Clients VALUES(27, 'Reno', 'Jean', '78 Boulevard de Lyon', '51200', 'Montmirail');
INSERT Clients VALUES(28, 'Lanvin', 'Gérard', '84 avenue de l''aile ou la cuisse', '92100', 'Boulogne-Billancourt');
INSERT Clients VALUES(29, 'Tautou', 'Audrey', 'rue de Montmartre', '63110', 'Beaumont');
INSERT Clients VALUES(30, 'Cotillard', 'Marion', '45 rue de la Même', '13001', 'Marseille');
INSERT Clients VALUES(31, 'Duris', 'Romain', '76 rue de l''arnaqueur', '06000', 'Nice');
INSERT Clients VALUES(32, 'Depardieu', 'Gérard', '57 rue du conte de Monté-Cristo', '36000', 'Châteauroux');
INSERT Clients VALUES(33, 'Youn', 'Michael', 'rue de la beuze', '92150', 'Suresnes');
INSERT Clients VALUES(34, 'Poelvoorde', 'Benoït', '22 rue du Boulet', '22500', 'Paimpol');
INSERT Clients VALUES(35, 'Paradis', 'Vanessa', '12 rue des arnaqueurs', '94100', 'Saint-Maur-des-Fossés');
INSERT Clients VALUES(36, 'Wilson', 'Lambert', '100 rue de Dieu', '92200', 'Neuilly-sur-Seine');
INSERT Clients VALUES(37, 'Garcia', 'José', '65 rue de la vérité', '75001', 'Paris');
INSERT Clients VALUES(38, 'Luchini', 'Fabrice', '73 rue de Beaumarchais', '75016', 'Paris');
INSERT Clients VALUES(39, 'Baye', 'Nathalie', '33 rue de Vénus', '27150', 'Mainneville');
INSERT Clients VALUES(40, 'Magimel', 'Benoït', '47 rue des petits mouchoirs', '33950', 'Lége-Cap-Ferret');
INSERT Clients VALUES(41, 'Cluzet', 'François', '7 rue des apprentis', '75018', 'Paris');
INSERT Clients VALUES(42, 'Frot', 'Catherine', 'rue Odette', '69110', 'Sainte Foy-les-Lyon');
INSERT Clients VALUES(43, 'Dupontel', 'Albert', '11 impasse de Bernie', '78100', 'Saintermain-en-Laye');
INSERT Clients VALUES(44, 'Huppert', 'Isabelle', '8 rue des femmes', '75002', 'Paris');
INSERT Clients VALUES(45, 'Deneuve', 'Catherine', '12 rue de Rochefort', '50100', 'Cherbourg-Octeville');
INSERT Clients VALUES(46, 'de France', 'Cécile', '17 rue de l''auberge espagnole', '08000', 'Charlesville-Mézières');

INSERT Fiches VALUES(9909, 20, GETDATE()-284, GETDATE()-282, 'SO');
INSERT LignesFic VALUES(9909, 1, 'A10', GETDATE()-284, DATEADD(HH, 6, GETDATE()-284));
INSERT LignesFic VALUES(9909, 2, 'S01', GETDATE()-284, DATEADD(HH, 6, GETDATE()-282));
INSERT Fiches VALUES(9910, 21, GETDATE()-68, NULL, 'RE');
INSERT LignesFic VALUES(9910, 1, 'P01', GETDATE()-68, DATEADD(HH, 6, GETDATE()-59));
INSERT LignesFic VALUES(9910, 2, 'S01', GETDATE()-68, DATEADD(HH, 6, GETDATE()-65));
INSERT LignesFic VALUES(9910, 3, 'A02', GETDATE()-68, DATEADD(HH, 6, GETDATE()-66));
INSERT LignesFic VALUES(9910, 4, 'F03', GETDATE()-68, DATEADD(HH, 6, GETDATE()-62));
INSERT LignesFic VALUES(9910, 5, 'F22', GETDATE()-68, DATEADD(HH, 6, GETDATE()-63));
INSERT Fiches VALUES(9911, 22, GETDATE()-182, GETDATE()-171, 'SO');
INSERT LignesFic VALUES(9911, 1, 'A04', GETDATE()-182, DATEADD(HH, 6, GETDATE()-176));
INSERT LignesFic VALUES(9911, 2, 'A10', GETDATE()-182, DATEADD(HH, 6, GETDATE()-177));
INSERT LignesFic VALUES(9911, 3, 'P01', GETDATE()-182, DATEADD(HH, 6, GETDATE()-179));
INSERT Fiches VALUES(9912, 23, GETDATE()-355, GETDATE()-342, 'SO');
INSERT LignesFic VALUES(9912, 1, 'F05', GETDATE()-355, DATEADD(HH, 6, GETDATE()-351));
INSERT LignesFic VALUES(9912, 2, 'A04', GETDATE()-355, DATEADD(HH, 6, GETDATE()-352));
INSERT LignesFic VALUES(9912, 3, 'F10', GETDATE()-355, DATEADD(HH, 6, GETDATE()-348));
INSERT Fiches VALUES(9913, 24, GETDATE()-319, NULL, 'RE');
INSERT LignesFic VALUES(9913, 1, 'F23', GETDATE()-319, DATEADD(HH, 6, GETDATE()-316));
INSERT LignesFic VALUES(9913, 2, 'F64', GETDATE()-319, DATEADD(HH, 6, GETDATE()-312));
INSERT LignesFic VALUES(9913, 3, 'F22', GETDATE()-319, DATEADD(HH, 6, GETDATE()-314));
INSERT LignesFic VALUES(9913, 4, 'F02', GETDATE()-319, DATEADD(HH, 6, GETDATE()-315));
INSERT LignesFic VALUES(9913, 5, 'F61', GETDATE()-319, DATEADD(HH, 6, GETDATE()-315));
INSERT Fiches VALUES(9914, 25, GETDATE()-351, GETDATE()-343, 'SO');
INSERT LignesFic VALUES(9914, 1, 'F03', GETDATE()-351, DATEADD(HH, 6, GETDATE()-349));
INSERT LignesFic VALUES(9914, 2, 'A11', GETDATE()-351, DATEADD(HH, 6, GETDATE()-345));
INSERT LignesFic VALUES(9914, 3, 'F22', GETDATE()-351, DATEADD(HH, 6, GETDATE()-350));
INSERT LignesFic VALUES(9914, 4, 'F01', GETDATE()-351, DATEADD(HH, 6, GETDATE()-350));
INSERT Fiches VALUES(9915, 26, GETDATE()-276, GETDATE()-267, 'SO');
INSERT LignesFic VALUES(9915, 1, 'F10', GETDATE()-276, DATEADD(HH, 6, GETDATE()-268));
INSERT LignesFic VALUES(9915, 2, 'F23', GETDATE()-276, DATEADD(HH, 6, GETDATE()-274));
INSERT LignesFic VALUES(9915, 3, 'F64', GETDATE()-276, DATEADD(HH, 6, GETDATE()-274));
INSERT Fiches VALUES(9916, 27, GETDATE()-158, GETDATE()-144, 'SO');
INSERT LignesFic VALUES(9916, 1, 'A11', GETDATE()-158, DATEADD(HH, 6, GETDATE()-150));
INSERT LignesFic VALUES(9916, 2, 'A02', GETDATE()-158, DATEADD(HH, 6, GETDATE()-158));
INSERT LignesFic VALUES(9916, 3, 'A03', GETDATE()-158, DATEADD(HH, 6, GETDATE()-146));
INSERT Fiches VALUES(9917, 28, GETDATE()-266, GETDATE()-258, 'SO');
INSERT LignesFic VALUES(9917, 1, 'P10', GETDATE()-266, DATEADD(HH, 6, GETDATE()-262));
INSERT LignesFic VALUES(9917, 2, 'F01', GETDATE()-266, DATEADD(HH, 6, GETDATE()-261));
INSERT Fiches VALUES(9918, 29, GETDATE()-204, NULL, 'RE');
INSERT LignesFic VALUES(9918, 1, 'A04', GETDATE()-204, DATEADD(HH, 6, GETDATE()-203));
INSERT LignesFic VALUES(9918, 2, 'P11', GETDATE()-204, DATEADD(HH, 6, GETDATE()-203));
INSERT Fiches VALUES(9919, 30, GETDATE()-242, GETDATE()-239, 'SO');
INSERT LignesFic VALUES(9919, 1, 'A04', GETDATE()-242, DATEADD(HH, 6, GETDATE()-240));
INSERT LignesFic VALUES(9919, 2, 'F60', GETDATE()-242, DATEADD(HH, 6, GETDATE()-241));
INSERT LignesFic VALUES(9919, 3, 'S01', GETDATE()-242, DATEADD(HH, 6, GETDATE()-242));
INSERT Fiches VALUES(9920, 31, GETDATE()-283, GETDATE()-281, 'SO');
INSERT LignesFic VALUES(9920, 1, 'A05', GETDATE()-283, DATEADD(HH, 6, GETDATE()-281));
INSERT LignesFic VALUES(9920, 2, 'P01', GETDATE()-283, DATEADD(HH, 6, GETDATE()-283));
INSERT LignesFic VALUES(9920, 3, 'S02', GETDATE()-283, DATEADD(HH, 6, GETDATE()-283));
INSERT Fiches VALUES(9921, 32, GETDATE()-318, NULL, 'RE');
INSERT LignesFic VALUES(9921, 1, 'P11', GETDATE()-318, DATEADD(HH, 6, GETDATE()-315));
INSERT Fiches VALUES(9922, 33, GETDATE()-226, GETDATE()-215, 'SO');
INSERT LignesFic VALUES(9922, 1, 'F02', GETDATE()-226, DATEADD(HH, 6, GETDATE()-220));
INSERT LignesFic VALUES(9922, 2, 'F01', GETDATE()-226, DATEADD(HH, 6, GETDATE()-222));
INSERT LignesFic VALUES(9922, 3, 'A10', GETDATE()-226, DATEADD(HH, 6, GETDATE()-219));
INSERT Fiches VALUES(9923, 34, GETDATE()-214, GETDATE()-210, 'SO');
INSERT LignesFic VALUES(9923, 1, 'A10', GETDATE()-214, DATEADD(HH, 6, GETDATE()-212));
INSERT LignesFic VALUES(9923, 2, 'A01', GETDATE()-214, DATEADD(HH, 6, GETDATE()-211));
INSERT Fiches VALUES(9924, 35, GETDATE()-161, NULL, 'RE');
INSERT LignesFic VALUES(9924, 1, 'A05', GETDATE()-161, DATEADD(HH, 6, GETDATE()-157));
INSERT LignesFic VALUES(9924, 2, 'F23', GETDATE()-161, DATEADD(HH, 6, GETDATE()-161));
INSERT Fiches VALUES(9925, 36, GETDATE()-346, NULL, 'RE');
INSERT LignesFic VALUES(9925, 1, 'P01', GETDATE()-346, DATEADD(HH, 6, GETDATE()-336));
INSERT LignesFic VALUES(9925, 2, 'F04', GETDATE()-346, DATEADD(HH, 6, GETDATE()-334));
INSERT Fiches VALUES(9926, 37, GETDATE()-195, NULL, 'RE');
INSERT LignesFic VALUES(9926, 1, 'A01', GETDATE()-195, DATEADD(HH, 6, GETDATE()-187));
INSERT LignesFic VALUES(9926, 2, 'F23', GETDATE()-195, DATEADD(HH, 6, GETDATE()-195));
INSERT Fiches VALUES(9927, 38, GETDATE()-275, GETDATE()-271, 'SO');
INSERT LignesFic VALUES(9927, 1, 'F02', GETDATE()-275, DATEADD(HH, 6, GETDATE()-274));
INSERT Fiches VALUES(9928, 39, GETDATE()-23, NULL, 'RE');
INSERT LignesFic VALUES(9928, 1, 'F63', GETDATE()-23, DATEADD(HH, 6, GETDATE()-12));
INSERT LignesFic VALUES(9928, 2, 'P11', GETDATE()-23, DATEADD(HH, 6, GETDATE()-13));
INSERT Fiches VALUES(9929, 40, GETDATE()-89, NULL, 'RE');
INSERT LignesFic VALUES(9929, 1, 'P01', GETDATE()-89, DATEADD(HH, 6, GETDATE()-87));
INSERT LignesFic VALUES(9929, 2, 'A04', GETDATE()-89, DATEADD(HH, 6, GETDATE()-88));
INSERT Fiches VALUES(9930, 41, GETDATE()-97, GETDATE()-86, 'SO');
INSERT LignesFic VALUES(9930, 1, 'F02', GETDATE()-97, DATEADD(HH, 6, GETDATE()-95));
INSERT Fiches VALUES(9931, 42, GETDATE()-176, GETDATE()-167, 'SO');
INSERT LignesFic VALUES(9931, 1, 'S01', GETDATE()-176, DATEADD(HH, 6, GETDATE()-174));
INSERT LignesFic VALUES(9931, 2, 'F21', GETDATE()-176, DATEADD(HH, 6, GETDATE()-175));
INSERT LignesFic VALUES(9931, 3, 'F10', GETDATE()-176, DATEADD(HH, 6, GETDATE()-176));
INSERT Fiches VALUES(9932, 43, GETDATE()-245, NULL, 'RE');
INSERT LignesFic VALUES(9932, 1, 'F50', GETDATE()-245, DATEADD(HH, 6, GETDATE()-245));
INSERT LignesFic VALUES(9932, 2, 'A02', GETDATE()-245, DATEADD(HH, 6, GETDATE()-245));
INSERT LignesFic VALUES(9932, 3, 'F63', GETDATE()-245, DATEADD(HH, 6, GETDATE()-244));
INSERT Fiches VALUES(9933, 44, GETDATE()-13, GETDATE()-2, 'SO');
INSERT LignesFic VALUES(9933, 1, 'P11', GETDATE()-13, DATEADD(HH, 6, GETDATE()-2));
INSERT LignesFic VALUES(9933, 2, 'A11', GETDATE()-13, DATEADD(HH, 6, GETDATE()-4));
INSERT LignesFic VALUES(9933, 3, 'F22', GETDATE()-13, DATEADD(HH, 6, GETDATE()-13));
INSERT Fiches VALUES(9934, 45, GETDATE()-306, GETDATE()-302, 'SO');
INSERT LignesFic VALUES(9934, 1, 'P10', GETDATE()-306, DATEADD(HH, 6, GETDATE()-306));
INSERT LignesFic VALUES(9934, 2, 'A11', GETDATE()-306, DATEADD(HH, 6, GETDATE()-306));
INSERT LignesFic VALUES(9934, 3, 'F21', GETDATE()-306, DATEADD(HH, 6, GETDATE()-305));

```

:one: Liste des clients (nom, prénom, adresse, code postal, ville) ayant au moins une fiche de location en cours.   
:two: Détail de la fiche de location de M. Dupond Jean de Paris (avec la désignation des articles loués, la date 
de départ et de retour).  
:three: Liste de tous les articles (référence, désignation et libellé de la catégorie) dont le libellé de la catégorie 
contient ski. 
:four: Calcul du montant de chaque fiche soldée et du montant total des fiches. 
:five: Calcul du nombre d’articles actuellement en cours de location. 
:six: Calcul du nombre d’articles loués, par client. 
:seven: Liste des clients qui ont effectué (ou sont en train d’effectuer) plus de 200€ de location. 
:eight: Liste de tous les articles (loués au moins une fois) et le nombre de fois où ils ont été loués, triés du plus 
loué au moins loué. 

:nine: Liste des fiches (n°, nom, prénom) de moins de 150€. 
Le langage de requête SQL avec SQL Server 
**10** Calcul de la moyenne des recettes de location de surf (combien peut-on espérer gagner pour une location 
d'un surf ?). 
**11** Calcul de la durée moyenne d'une location d'une paire de skis (en journées entières). 