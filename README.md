# Challenge Modélisation - Prédire l'effet sdu Fipronil sur l'abeille domestique

Vous arrivez à la fin de la section dédiée à la modélisation statistique au terme de ce quatrième module de Science des Données Biologiques 2. Vous avez maintenant un challenge à relever.

L'Union Européenne vient de lever l'interdiction de l'utilisation de néonicotinoïdes comme pesticides dans l'agriculture. Sous certaines conditions, le **Fipronil** est donc maintenant à nouveau autorisé, par exemple, pour la culture de la betterave. Malheureusement, ce pesticide a aussi des effets sur les insectes, dont les pollinisateurs. Vous êtes contacté pour modéliser son effet létal sur l'abeille domestique *Apis mellifera*.

Vous recevez deux jeux de données. L'un, nommé **train.rds** contient un set complet de données relatives à la mortalité de *A. mellifera* en présence de doses croissantes de Fipronil. Vous devez utiliser ce jeu de données pour modéliser le phénomène du mieux possible.

Ensuite, vous prédisez les taux de mortalité à l'aide de ce modèle à partir du second jeu de données nommé **test.rds**. Le code pour le faire est déjà dans le fichier R Markdown exemple dans le dossier `docs`. Vous devez ensuite soumettre votre réponse au challenge et tenter de monter le plus haut possible dans le classement.

**Lisez bien les instructions ci-dessous et assurez-vous de les avoir bien comprises avant de commencer votre travail !**

Vos propositions doivent être soumises via l'interface dans le cours : soumettez le fichier `.rds` qui est généré dans `/results`. Vous avez un document R Markdown exemple dans `docs` pour vous y aider. Vous pouvez soumettre autant de modèles que vous voulez, mais **vous devez donner un nom différent à chaque fois.** Vos résultats et votre progression seront affichés dans le tableau des scores. Pour chaque modèle soumis, vous devrez commiter un document `.Rmd` du même nom dans votre dépôt GitHub qui reprend votre analyse pour ce modèle en particulier. Démarrez toujours à partir d'une copie de `docs/lm_simple.Rmd` (ou de votre analyse précédente) que vous renommez. À partir du moment où vous avez soumis vos résultats, **n'éditez plus le fichier `.Rmd` qui a servi à la générer.**

**Votre objectif est de prédire du mieux possible la mortalité de l'abeille domestique pour les données tests.**

Les meilleures équipes seront nominées à la fin de la séance, et elles viendront exposer leur modèle devant la classe.

