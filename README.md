# responsiveProject
En local, Chrome et IE/Edge bloquent les imports nécessaire à Polymer avec l'erreur suivante :
"Imported resource from origin 'file://' has been blocked from loading by Cross-Origin Resource Sharing policy: Invalid response. 
Origin 'null' is therefore not allowed access"

Ceci est dû à une politique de ces navigateurs qui interdissent l'utilisation de l'Ajax pour les ressources locales.

Il faut fonc que le site soit sur un serveur web même local de type wamp.

Ce problème ne pose pas avec Firefox qui est plus souple au niveau de cette règle.
