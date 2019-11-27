<h2 align="center">Projet Ipssi Flask Python</h2>

### Que propose le site PythonAnywhere.com ?

Le site PythonAnywhere.com sert à la fois d'IDE (Environnement de développement) et d'hébergeur pour les projets basé sur la 
programation faite en langage Python, le tout en ligne. Le site offre également un accès aux interface de commande Python et 
Bash ainsi qu'un éditeur de code avec Syntax highlighting (mise en évidence de la syntaxte)

Il est possible de téléchargé sont projet en local ou en passant par un repository git. 
Les applications Web hébergées par le service peuvent être écrites à l'aide de n'importe quel framework d'application basé sur WSGI.

### Qu'est ce que FLASK ? Quels sites connus utilisent Flask ? 

Flask est un web framework petit et puissant (également appelé "microframework") utiliser en Python, le "micro" de microframework 
signifie que Flask vise à garder le noyau simple mais extensible. Il a la base était créé pour faire un poisson d'avril. Pour
l'installer rien de plus simple, il suffit de tapper cette commande ```$ pip install Flask```. Pinterest, Twilio, Airbnb et même le
sit web pour la campagne de Barack Obamas en 2012, ces quatres sites utilisent Flask.

### Les étapes que j'ai suivi

Pour herberger le projet:
- je me suis dans un premier temps créer un compte sur PythonAnywhere
- j'ai saisi la commande ```git clone``` dans le terminal Bash du site pour récupérer le projet sur le repository GitHub
- j'ai cliqué sur `Open Web Tab`pour pouvoir ajouter une nouvelle Web app
- après avoir choisi Flask et la version de Python j'ai pu créer ma nouvelle Web app à l'adresse `http://dmansuy.pythonanywhere.com/`

### Quelles difficultés avez-vous rencontrées ?

J'ai eu du mal à comprendre pourquoi la page `http://dmansuy.pythonanywhere.com/` m'afficher `Bienvenue sur Flask !` à la 
place du `Bienvenue` initialement prévu sur la route `\` présent dans le code app.py d'origine. J'ai découvert après quelques minutes d'investigation que mon fichier app.py avait été totalement réécrit pour laisser place la phrase `Bienvenue sur Flask !`. 
Après constatation de la modification j'ai changé le contenu de app.py avec le code d'origine.
 
### Les aspects techniques limitants du projet FLGAZ dans l'état initial selon moi

### Les menaces auxquelles un tel projet peut être soumis selon moi
