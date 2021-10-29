# InfoIndus

**Communication Interne**:
I2C, pi3b+ en master, n*arduino en slave

**Calcul des Consignes**:
Le calcul des consignes de actionneurs tourne sur la raspberry pi

# Web

**Interface Extérieur**:
->On connecte la pi via eduroam ou ethernet
->Serveur web: (django?) (c’est du python et c’est facile à utiliser)
->Difficile de contrôler facilement la pi en local: besoin de ssh pour débugger
->La serre doit restart automatiquement en cas de coupure

# Objectif:
Lire une tension et faire clignoter un potentiomètre via une interface web sur la raspberry, pour tester les protocoles
