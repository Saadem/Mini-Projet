###  **Régression Ridge vs Lasso**



Ce script compare la performance prédictive de la régression Ridge (pénalisation L2) et de la régression Lasso (pénalisation L1) à l’aide de données synthétiques générées selon un modèle linéaire.



#### &nbsp; **Dépendances requises**



Avant d’exécuter le script, rassurer d'avoir les bibliothèques suivantes (ou des versions équivalentes) :



\- numpy ≥ 1.21  

\- matplotlib ≥ 3.4  

\- scikit-learn ≥ 1.0



#### &nbsp;**Exécution du code**





1\. Ouvrez un terminal (ou Anaconda Prompt).

2\. Placez-vous dans le dossier contenant le fichier `figure\_ridge\_lasso.py`.

3\. Tapez la commande suivante : 



&nbsp;  python figure\_ridge\_lasso.py



4\. Le script générera une figure nommée `figure\_ridge\_lasso.png` dans le dossier courant. Elle représente l’évolution de la RMSE en fonction de la valeur de λ pour les deux méthodes(Ridge et Lasso).



Tous les paramètres (nombre d’observations, bruit, plage de λ, etc.) sont modifiables directement dans le fichier Python.





