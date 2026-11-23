---
title: "Perte attendue (PD, LGD, EAD)"
aliases: ["PD", "LGD", "EAD", "expected loss"]
---
> Ce qu'un prêteur s'attend à perdre en moyenne sur un crédit : la probabilité que le client fasse défaut, multipliée par la part perdue en cas de défaut et par le montant exposé.

## Comment ça marche

**Perte attendue** (**expected loss**, EL) = **PD** × **LGD** × **EAD**.

- **PD** (**probability of default**) : la probabilité que l'emprunteur fasse défaut, en général sur un an.
- **LGD** (**loss given default**) : la part de l'exposition perdue en cas de défaut, c'est-à-dire 1 moins le taux de récupération.
- **EAD** (**exposure at default**) : le montant dû au moment du défaut, y compris la partie d'une ligne de crédit que le client aurait tirée entre-temps.

Chaque facteur répond à une question différente. La PD dépend du client : ses revenus, son endettement, son historique. La LGD dépend surtout de l'actif et de la structure : la LTV, le rang, la facilité à saisir et à vendre l'actif. L'EAD dépend du contrat : montant tiré, lignes non tirées, intérêts courus.

Dans le cadre de Bâle, les fonds propres d'une banque couvrent les pertes inattendues ; la perte attendue est traitée à part, par les provisions. Le prix d'un crédit doit donc couvrir au moins la perte attendue, plus le coût des fonds propres que le prêteur immobilise.

## Les chiffres à connaître

La note explicative de la BRI sur les formules de Bâle II calcule la perte attendue sur un horizon d'un an : PD multipliée par l'EAD, puis par la LGD.

Exemple, avec des hypothèses : un client a une PD de 2 %. Son yacht vaut 20 millions ; vendu de force à 60 % de sa valeur, moins 1 million de frais, il rapporte 11 millions.

- Prêt de 16 millions (LTV 80 %) : perte en cas de défaut 5 millions, LGD de 31,25 %, perte attendue 0,02 × 0,3125 × 16 millions = **100 000** par an.
- Prêt de 10 millions (LTV 50 %) : les 11 millions récupérés couvrent la dette ; la perte attendue est **nulle**.

La même PD donne deux risques très différents : c'est la LTV, par la LGD, qui fait la différence.

## En pratique chez un debt advisor

- Un fonds de dette qui accepte un client à PD élevée (revenus irréguliers, dettes ailleurs) compense par une LGD faible : LTV basse, premier rang, actif facile à saisir.
- Pour obtenir un meilleur prix, on agit sur ce que le prêteur peut chiffrer : baisser l'EAD (montant plus petit), baisser la LGD (sûreté de plus, meilleur rang), documenter la PD (revenus, historique).

## Pièges

- Croire qu'une bonne sûreté efface le risque : elle réduit la LGD, pas la PD, et un défaut coûte toujours du temps et des frais.
- Oublier la partie non tirée d'une ligne de crédit dans l'EAD.
- Calculer la récupération sur la valeur de marché au lieu de la valeur de vente forcée nette de frais.

## Liens

- Hub : [[Fondamentaux du crédit/Hub - Fondamentaux du crédit|Hub - Fondamentaux du crédit]]
- Notions voisines : [[Fondamentaux du crédit/Loan-to-value (LTV)|Loan-to-value (LTV)]], [[Fondamentaux du crédit/Séniorité et rang|Séniorité et rang]], [[Fondamentaux du crédit/Valeur de marché et valeur de réalisation forcée|Valeur de marché et valeur de réalisation forcée]], [[Fondamentaux du crédit/Prix d'un crédit|Prix d'un crédit]], [[Fondamentaux du crédit/Bankability et les C du crédit|Bankability et les C du crédit]]
- Fiche CFA : How do you decompose an expected credit loss?

## Sources

- An Explanatory Note on the Basel II IRB Risk Weight Functions (juillet 2005), Banque des règlements internationaux, https://www.bis.org/bcbs/irbriskweight.htm, consulté le 2026-11-20
- Credit Risk, refresher reading 2026, CFA Institute, https://www.cfainstitute.org/insights/professional-learning/refresher-readings/2026/credit-risk, consulté le 2026-11-20

## Autotest

> [!question]- Comment se décompose la perte attendue d'un crédit ?
> Probabilité de défaut × perte en cas de défaut × exposition au moment du défaut (PD × LGD × EAD).

> [!question]- De quoi dépend surtout la LGD ?
> De l'actif et de la structure : la LTV, le rang de la sûreté, la facilité à saisir et à vendre l'actif.

> [!question]- Pourquoi deux prêts au même client n'ont-ils pas la même perte attendue ?
> Parce que la PD est la même mais la LGD change avec la LTV : un prêt à LTV basse peut avoir une perte attendue nulle.

> [!question]- Que couvrent les fonds propres d'une banque dans le cadre de Bâle ?
> Les pertes inattendues ; la perte attendue est couverte à part, par les provisions et par le prix du crédit.
