## S1J1 — Comprendre un LLM
   - Définition en 1 phrase : un systeme de prédiction du prochain token. Token: unité atomique manipulée par le LLM ( 3-4 caractere, parfois un mot entier, parfois un fragment.. esemple: manger= 1 token, démoduler= 3 token). Probabilité = détermine le choix d'un token,donc propabilité est différence des token. Le LLM choisit le prochain token selon ces probabilités. LLM se compose de 2 fichiers : fichier parametres ( 140 gb le poids du modele le résultat de l'entrainement / fichier run.c ( 500 lignes de code C ) : programme qui execute le modele. 
   - Analogie RF_LLM (perso) : Imaginé comme un gros démodulateur qui choisis parmi N condidat, le codidat le plus probable.
   - Ce qui me trouble encore : le fonctionnement du neural systeme et le faite qu'on peut juste le calibrer et non pas le comprendre. Si on ne le comprend pas, commet il a ete créé.
- RIR : 3 / Temps : 60 min
