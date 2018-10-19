# newrepository
new repository
<!DOCTYPE html>
<html>
<body>
<h1>INSTALLATION</h1>
<p>You can install GitHub Desktop on supported Microsoft Windows or OS X operating systems.<br/>
 Before you set up GitHub Desktop, you must already have a GitHub or GitHub Enterprise account.<br/>
 For more information on creating a GitHub account, see "Signing up for a new GitHub account".<br/>
For a GitHub Enterprise account, contact your GitHub Enterprise site administrator.</p>
 <h1>CONFIGURATION</h1>
 <p>Comme vous avez pu l'entrevoir au chapitre 1, vous pouvez spécifier les paramètres de configuration de Git avec la commande git config. <br/>
Une des premières choses que vous avez faites a été de paramétrer votre nom et votre adresse e-mail :<br/>
 $ git config --global user.name "John Doe"<br/>
$ git config --global user.email johndoe@example.com<br/>
À présent, vous allez apprendre quelques unes des options similaires les plus intéressantes pour paramétrer votre usage de Git.<br/>
 Vous avez vu des détails de configuration simple de Git au premier chapitre, mais nous allons les réviser.<br/>
Git utilise une série de fichiers de configuration pour déterminer son comportement selon votre personnalisation.<br/>
Le premier endroit que Git visite est le fichier /etc/gitconfig qui contient des valeurs pour tous <br/>
les utilisateurs du système et tous leurs dépôts. Si vous passez l'option --system à git config, il lit et écrit ce fichier.<br/>
 L'endroit suivant visité par Git est le fichier ~/.gitconfig qui est spécifique à chaque utilisateur. <br/>
Vous pouvez faire lire et écrire Git dans ce fichier au moyen de l'option --global.<br/>
 Enfin, Git recherche des valeurs de configuration dans le fichier de configuration du répertoire Git (.git/config) du dépôt en cours d'utilisation.<br/>
Ces valeurs sont spécifiques à un unique dépôt.<br/>
Chaque niveau surcharge le niveau précédent, ce qui signifie que les valeurs dans .git/config écrasent celles dans /etc/gitconfig.<br/>
Vous pouvez positionner ces valeurs manuellement en éditant le fichier et en utilisant la syntaxe correcte,<br/>
mais il reste généralement plus facile de lancer la commande git config.</p>
<h1>LICENCE</h1>
<p>Public repositories on GitHub are often used to share open source software. <br/>
For your repository to truly be open source, you'll need to license it so that others are free to use,<br/>
change, and distribute the software.
</p>
</body>
</html>
