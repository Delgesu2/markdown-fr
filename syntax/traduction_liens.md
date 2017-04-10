#Liens

Markdown supporte deux styles de lien: en ligne et référence.
Dans les deux styles, le texte du lien est délimité par [des crochets].
Pour créer un lien en ligne, utiliser une paire de parenthèses régulières immédiatement après le crochet fermant le texte du lien. A l'intérieur des parenthèses, mettez l'URL sur laquelle vous voulez que le lien pointe, suivi d'un titre optionnel pour le lien, entouré de guillemets. Par exemple: 
```markdown
[Je suis un lien de syle en-ligne](https://www.google.com)
[Je suis un lien  de style en-ligne avec un titre](https://www.google.com "Google's Homepage")
[Je suis un lien de style-référence][Texte de référence insensible à la casse]
[Je suis une référence relative à un fichier de dépôt](../blob/master/LICENSE)
```

> Je passe quelques paragraphes. L'essentiel
> est de démontrer les possibilités et la 
>facilité de Markdown.

*J'aurais pu aussi l'écrire comme ça.*

>*ou un mélange des deux*


**Github** et **GitBook** supportent l'autolien d'URL. Ils redirigeront automatiquement l'URL, ainsi si vous voulez mettre un ien vers une URL, vous pouvez simplement entrer une URL et le texte sera transformer en un lien vers cette URL.