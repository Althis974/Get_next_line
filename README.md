# GET_NEXT_LINE

# Introduction

Vous commencez maintenant à vous rendre compte qu’à chaque fois que vous retrouvez
dans la situation de lire des données depuis un file descriptor et que cette donnée
n’est pas d’une taille connue à l’avance, c’est compliqué. Quelle taille de buffer choisir ?
Combien de fois lire sur le file descriptor pour retrouver la donnée ?
Il est parfaitement naturel et commun en programmation de vouloir lire une “ligne”
terminée par un retour à la ligne depuis un file descriptor. Par exemple chaque commande
que vous tapez dans votre shell ou bien chaque ligne lue depuis un fichier plat.
Grâce au projet get_next_line, vous allez pouvoir écrire une bonne fois pour toute
une fonction vous permettant de lire une ligne terminée par une retour à la ligne depuis
un file descriptor, l’ajouter à votre libft si le coeur vous en dit, et surtout l’utiliser dans
tous vos projets suivants qui en auront besoin.

# Objectifs

Ce projet va non seulement vous permettre d’ajouter une fonction très pratique à
votre collection, mais vous permettra également d’aborder un nouvel élément surprenant
de la programmation en C : les variables statiques.
Vous experimenterez également plus profondément les allocations, qu’elles aient lieu
sur la pile ou sur le tas, la manipulation et le cycle de vie d’un buffer, et la complexité
inattendue qu’implique l’utilisation d’une ou plusieurs variables statiques.
Bien entendu, vous renforcerez également votre rigueur grâce au respect de la Norme,
mais aussi en découvrant que l’état initial d’un variable dans une fonction peut varier
d’un appel à l’autre de cette fonction...
