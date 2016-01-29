# projet-M2-SSI
Ce projet constitue projet de fin de cycle en master 2 sécurité des systèmes informatiques.

Le projet a été donné par madame Lynda Mokdad (enseigante à l'université Paris-Est Créteil) et est defini comme suit:

Il s’agit de réaliser une application client /serveur sécurisée dont le serveur
est une banque et les clients peuvent se connecter pour consulter leur
compte, effectuer des virements, etc.

On suppose :

• Le serveur distribue une clé publique

• Un client qui veut se connecter au serveur envoie une clé de
session cryptée avec la clé publique du serveur

• Le serveur décrypte la clé de session avec sa clé privée

Objectifs :

1. Etablir un échange sécurisé entre le serveur et le client tel que le
client puisse envoyer des requêtes pour consulter son compte,
effectuer un virement, etc.
2. Proposer une solution pour garantir l’authenticité des clients.
