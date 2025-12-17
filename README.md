#  Prédiction d'approbation de prêt bancaire avec régression logistique
Ce projet a pour objectif de prédire si une demande de prêt sera **approuvée** ou **refusée** à l'aide d'un modèle de **régression logistique**.
##  Objectif
Utiliser des données relatives aux demandeurs de prêt (revenu, emploi, statut familial, etc.) afin de prédire automatiquement si leur demande sera approuvée ou non.
##  Dataset
Le dataset utilisé est `loan-train.csv`, contenant les colonnes suivantes :
- `Loan_ID` : Identifiant du prêt
- `Gender` : Sexe du demandeur
- `Married` : Statut marital
- `Dependents` : Nombre de personnes à charge
- `Education` : Niveau d'éducation
- `Self_Employed` : Travail indépendant ou non
- `ApplicantIncome` : Revenu du demandeur
- `CoapplicantIncome` : Revenu du co-demandeur
- `LoanAmount` : Montant du prêt demandé
- `Loan_Amount_Term` : Durée du prêt
- `Credit_History` : Historique de crédit (1 = bon, 0 = mauvais)
- `Property_Area` : Zone de résidence (urbaine, semi-urbaine, rurale)
- `Loan_Status` : Cible à prédire (Y = approuvé, N = refusé)

## Plan du travail
- chargement du données 
- Préparation des données :
    - nettoyage des valeurs manquantes 
    - supression des doublons 
    - Encodage des variables catégorielles
- Analyse exploratoire des données (EDA): 
    - statistiques descriptives
    - analyse de la variable cible : Loan_Status
    - analyse univariée des variables explicatives 
    -  analyse bivariée ( variable cible VS les autres variables)
- Modéle de la régression logistique : 
    - Préparation des données pour le modéle 
    - Entraînement du modéle
    - Evaluation du modéle
