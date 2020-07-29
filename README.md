# Prévoir la demande en électrité
Travailler sur les énergies renouvelable. Améliorer l'adéquation entre l'offre et la demande.  

Méthodologie : 
- Corriger les données de consommation mensuelles de l'effet température (dues au chauffage électrique) en utilisant une régression linéaire.
- Effectuer une désaisonnalisation de la consommation obtenue après correction, grâce aux moyennes mobiles.
- Effectuer une prévision de la consommation (corrigée de l'effet température) sur un an, en utilisant la méthode de Holt Winters (lissage exponentiel) puis la méthode SARIMA sur la série temporelle.  

Outils : 
- Python
- Régression linéaire
- séries temporelles (AR, MA, ARMA, ARIMA, etc.) 
