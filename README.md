# Formulaire de Contact

Ce formulaire de contact HTML avec une fonctionnalité PHP permet aux utilisateurs d'envoyer des messages à une adresse e-mail spécifiée. Les utilisateurs peuvent saisir leur nom, leur adresse e-mail, leur numéro de téléphone et un message. Le formulaire inclut également un mode sombre pour un thème alternatif.

## Utilisation

1. Assurez-vous d'avoir accès aux feuilles de style CSS `style.css` et `contact.css` pour appliquer les styles au formulaire.

2. Configurez l'action du formulaire :
   - L'action du formulaire est définie sur `contact.php`, vous devez donc créer un fichier PHP (par exemple, `contact.php`) sur votre serveur pour traiter les données du formulaire.
   - Ajustez l'attribut `action` de la balise `<form>` pour correspondre au nom de fichier de votre fichier de traitement PHP.

3. Personnalisez le formulaire :
   - Vous pouvez modifier les champs du formulaire, les libellés, les emplacements de texte et les styles selon vos besoins.

4. Configurez un serveur Web avec le support de PHP :
   - Pour tester le formulaire en local, vous pouvez utiliser des outils tels que XAMPP, WAMP ou MAMP.

## Mode Sombre

Ce formulaire propose un bouton de bascule en mode sombre. Lorsque les utilisateurs cliquent sur le bouton "Mode sombre", le formulaire passera en mode sombre. Le mode sombre peut être désactivé en cliquant sur le bouton "Mode clair".

## Validation du Formulaire

Le formulaire inclut une fonction de validation côté client (`validateForm()`) pour vérifier si l'adresse e-mail est valide et si le numéro de téléphone contient uniquement des chiffres. Une validation côté serveur supplémentaire est recommandée pour renforcer la sécurité.

## Configuration de l'E-mail

Assurez-vous que votre serveur est configuré pour envoyer des e-mails. Vous devrez peut-être configurer les paramètres e-mail appropriés ou utiliser une bibliothèque telle que PHPMailer pour gérer l'envoi d'e-mails de manière plus sécurisée.

## Remarque

Gardez à l'esprit que ce formulaire de contact est relativement basique et peut ne pas inclure toutes les mesures de sécurité nécessaires pour prévenir le spam ou les attaques. Il est conseillé de mettre en place des mesures de sécurité supplémentaires, telles que CAPTCHA ou la validation des entrées, pour renforcer la sécurité du formulaire.

N'hésitez pas à personnaliser le formulaire selon vos besoins, et bonne chance avec votre projet !

## Prérequis

- PHP 5.x ou version supérieure
- Serveur Web avec prise en charge de PHP

## Auteur

Ce projet a été développé par [Nerlyss1].
