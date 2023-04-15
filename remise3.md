# Énoncé travail pratique - remise #3



## Produits (20% +10% bonus)



Votre compagnie d'assurance doit implémenter au moins 2 produits spécifiquement destinés au marché des produits sur deux têtes. Dans ces produits, on doit retrouver:



- Au moins 1 produit versant une rente aux assurés
- Au moins 1 produit versant une assurance vie aux assurés



Vos produits doivent utiliser l'interface `produit` et retourner une fonction utilisant l'interface `contrat` (tel que développé à la remise #1). Enregistrez vos produits en les envoyant au serveur de l'autorité (tel que présenté dans l'énoncé de la remise #1)  (20 %) 



### Points Bonus 
- Ajouter un produit qui contient une composante d'invalidité ou de maladie grave. (+10%)


## Tarification (60% +50% bonus)


Pour évaluer vos produits, vous aurez besoin d'émettre une hypothèse quant à la dépendance entre les vies. Les observations fournies à la remise précédente contiennent (à votre insu!) des relations entre les différents assurés. Le fichier [lien_assure.csv](abc) contient les données qui vous permettra d'associer les conjoints dans le jeu de données initial. 



- À la lumière de ces observations, est-ce que vous devriez revoir la tarification des produits sur une tête? Justifiez votre réponse (10%)



- Comparer l'impact en $ de l'hypothèse de dépendance state-dependance sur la prime de ces 3 couples pour vos deux produits. Discutez ces résultats et énoncez ce que vous utiliserez pour tarifer chacun des produits. (50%) 
    - un homme de 25 ans et une femme de 25 ans
    - un homme de 50 ans et une femme de 50 ans
    - un homme de 25 ans et une femme de 50 ans



### Points Bonus 



   1. Évaluez l'impact de générer un état additionnel pour tenir compte de la dépendance entre un conjoint pouvant avoir une prestation associée à une maladie grave ou invalidité (+20%)
   2. Évaluez l'impact en $ de modéliser la relation entre les fonctions de survies marginales des membres du couple avec une copule. Décrivez de façon succincte votre approche et discutez de vos résultats (+20%). Cette méthode peut être utilisée pour tarifer vos produits.
   3. Évaluez l'impact en $ de modéliser la relation de dépendance entre les conjoints en utilisant la notion d'âge équivalent. Décrivez de façon succincte votre approche et discutez de vos résultats (+10%). Cette méthode peut être utilisée pour tarifer vos produits.




## Ventes (10%)



Les ventes de vos produits sur deux têtes totalisent 10 000 000$ en prime. Présentez la distribution de ces ventes (10%).



## Réserve (10%)



Calculez l'évolution des réserves pour vos ventes pour les 10 prochaines années pour chacune des lignes d'affaires (10 %)




## Scénario de stress additionnel



   La dépendance entre les durées de vie future des conjoints est 10% plus forte que prévu à partir de l'année 5. 



Comme pour les autres scénarios, vous devrez présenter les impacts sur la profitabilité, par ligne d'affaires, pour les années 6 à 10. 



L'analyse des scénarios de stress sera remise à la remise 4, 



## Livrable



1. L'enregistrement d'au moins deux produits sur deux têtes (20% / +10%)
2. Un rapport en PDF d'au plus 3 pages (excluant figure et annexes) contenant:  (80%)
   
   1. Justification de la tarification des polices à une tête (10%)
   2. Discussion des comparaisons des hypothèses de dépendances (50%)
   3. Présentation de la distribution des ventes (10%)
   4. Projection des réserves par ligne d'affaires (10%)
   5. Une description des points bonus effectués (+x%)