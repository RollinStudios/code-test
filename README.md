# Conditions du test de code

1. Vous disposez de 1 heure pour finaliser le test.
2. Le test doit être fait en partagant votre écran en tout temps.
3. Vous avez le droit d'utiliser Google pour faire des recherches, mais vous devez montrer vos recherches à l'écran.
4. Vous n'avez pas le droit d'utiliser ChatGPT pour faire ce test. Si vous utilisez un modèle AI tel que ClaudeAI ou ChatGPT, vous serez automatiquement disqualifié.

## Commencement

1. Clonez le repository Git sur votre machine locale.
2. Ouvrir l'image "design.jpg" et "design_mobile.jpg" observer le design.

## Test de code

Note: Vous trouverez dans le repository les images requises. Les couleurs, textes et liens sont dans ce document, dans la section "informations".

1. Créer une nouvelle branche git nommée "test-technique"

2. En partagant votre écran, veuillez coder le design dans le fichier index.html en utilisant les bon éléments HTML et styles CSS nécessaires. Veuillez vous assurer de bien respecter les bonnes pratiques du web.

3. Lorsque l’utilisateur clique sur "I am a customer" ou "I am a producer", l’élément sélectionné doit changer de couleur en appliquant une classe CSS active. Cette classe permet d’indiquer visuellement le choix de l’utilisateur. De plus, la valeur d’un champ input de type hidden doit être mise à jour afin que l’information soit transmise correctement lors de l’envoi du formulaire.

4. Connecter le formulaire à l’aide d’un script PHP, effectuer une validation des données reçues, puis renvoyer une réponse appropriée en fonction du résultat de cette validation.

Le formulaire devrais envoyer 3 champs: Customer type, First Name, Email.

Utilisez du code PHP moderne et assurez-vous de valider correctement les types de données reçues via le formulaire.
Vous êtes libres de choisir la méthode de validation, toutefois nous recommandons l’utilisation du Symfony Validator ou de Laminas Validator. Vous trouverez les liens vers leur documentation dans la section Informations.

5. Si il vous reste du temps, veuillez rendre le design responsive sous mobile. Vous retrouverez le design mobile sous l'image "design_mobile.jpg", assurez-vous que les éléments se positionnent les uns au dessus des autres (stack) à partir de 1024px et en dessous.

6. Veuillez commettre (commit) votre code puis créer une pull request vers la branche principale (main) pour finaliser votre test.

### Informations:

Couleur vert (background): #c9dc94

Couleur vert pale: #E3EAC7

Couleur bleu: #2190BC

Couleur bleu pale: #deeef5

Couleur gris (input): #F6F3F2

Couleur blanc: #FFFFFF

Symfony Validator: https://symfony.com/doc/current/components/validator.html

Laminas Validator: https://docs.laminas.dev/laminas-validator/ 

Lien socials:
Facebook: https://www.facebook.com/
Bluesky: https://bsky.app/
Instagram: https://www.instagram.com/


### Considérations

1. Vous pouvez mettre votre css dans la balise de <style> mais une feuille externe vous donnerais des points supplémentaires.
2. Assurez-vous d'utiliser le bon éléments HTML aux bons endroits.
3. Un code sématique n'est pas exigé, mais vous donnerais des points supplémentaires.

