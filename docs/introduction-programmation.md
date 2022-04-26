# Introduction à la programmation

## Mise en contexte

* Un ordinateur est une machine électronique programmable et capable de mémoriser, de retrouver et de traiter des données.​

* Depuis que vous êtes petits, vous avez appris à « faire des choses » : ​
  * lever la main ;
  * saisir le coin supérieur droit de la page ; 
  * déplacer la main gauche à droite ; ​
  * ramener la main à sa position initiale.​
  * etc.​

* Malheureusement, l’ordinateur n’est pas intelligent.​
  * Il n’a donc pas d’aptitudes à raisonner. ​
  * Il ne peut pas analyser un problème et y apporter une solution. ​

*** Mais il sait très bien obéir aux instructions et fera exactement tout ce qu’on lui dira de faire…  (SANS SE PLAINDRE)​**

**C’est donc le programmeur qui se charge de l’étape de résolution : il doit définir une solution et la transmettre à l’ordinateur. L’un des avantages d’utiliser un ordinateur plutôt qu’un humain, c’est ????​**

## Définitions

### Programmation​

Travail consistant à définir une séquence d’instructions qui seront exécutées par un ordinateur.​

La programmation se divise en deux parties ​:
* Résoudre le problème (algorithme)​ : Déterminer le travail que l’ordinateur doit accomplir.​
*Mettre en œuvre la solution retenue (Programmer).

### Programme​

Séquence d’instructions indiquant les opérations qu’un ordinateur doit effectuer. ​

Un bon programme :​

* doit être fonctionnel (qu’il accomplisse la tâche qu’on lui demande);​
* peut être lu et compris;​
* peut être modifié, si nécessaire;​
* respecte l’échéancier et le budget fixés.

### Résolution d'un problème​

#### Analyse 
Comprendre (définir) le problème. Cette étape est primordiale. Comment faire un programme si vous ne comprenez pas ce qu’il doit faire ????​​

#### Solution générale (algorithme) 
Définir une séquence d’opérations permettant de résoudre le problème dans un langage de tous les jours.​​

#### Vérification 
Effectuer ces opérations pour voir si la solution résout effectivement le problème.

### Mise en oeuvre du programme

#### Solution particulière (programme) 
Traduire l’algorithme dans un langage de programmation.​

#### Mise au point
Faire exécuter les instructions par l’ordinateur. Vérifier les résultats et corriger le programme jusqu’à ce qu’il fonctionne correctement.​

#### Utilisation 
Se servir du programme.

### Algorithme 
Séquence d’opérations à effectuer pour résoudre un problème en un nombre fini d’étapes.​

Vous faites des algorithmes tous les jours ! Vous êtes étonnés ? Eh oui! puisqu’un algorithme est simplement une description verbale ou écrite indiquant l’enchaînement des actions nécessaires à l’accomplissement d’une tâche.​

Exemple: Algorithme pour démarrer une automobile

##Étapes à suivre pour réaliser un algorithme ​

1. S’assurer de bien comprendre le problème à résoudre ; ​

2. Réaliser un exemple concret ; ​

3. Faire une première ébauche d’une solution envisagée ; ​

4. Identifier de façon claire les variables en entrée, les variables en sortie et les constantes ; ​

5. Considérer chaque étape et les détailler si cela s’avère nécessaire ; ​

6. Lorsque l’algorithme est suffisamment clair, faire la trace ; ​

7. Traduire l’algorithme dans un langage de programmation ; ​

8. Faire les jeux d’essais.

### Instructions
Une instruction est une opération élémentaire d’un algorithme. ​
C’est une commande que l’interlocuteur peut comprendre et réaliser.​

Une instruction précise : ​

le nom de l’opération à effectuer (lire, écrire, additionner, comparer...)​

les données qui font l’objet de l’opération.

### Langages de programmation
* Ensemble de règles, de symboles et de mots servant à écrire des programmes.​

* Pour rédiger un programme, on n’emploie pas une langue comme le français ou l’anglais. On utilise plutôt un langage de programmation, qui permet d’écrire uniquement des instructions que l’ordinateur peut exécuter. ​

* Petit groupe de mots (if then else while)​

* Symboles mathématiques +-*/​

* Ensemble de règles de grammaire très précises​

* Écrire un programme consiste à traduire un algorithme dans un langage de programmation. 

## <span style="color:red">Comme on apprend la logique de la programmation, le cours de **Programmation 1** pourrait se donner dans **n’importe quel langage**.​</span>

## C\#

C# (prononcé C sharp) est un langage de programmation orienté objet à typage fort, créé par la société Microsoft, et notamment un de ses employés, Anders Hejlsberg, le créateur du langage Delphi.​​

C# est un langage développé par Microsoft dans le but de contrer la popularité de Java et qui selon ses concepteurs est:​

* Simple​
* Orienté Objet ​
* Robuste et sûr​
* Multitâches

**Pourquoi notre département a choisi C# pour débuter votre initiation à la programmation?​**

* Très populaire dans l'industrie​
* Le plus documenté sur le WEB​
* Syntaxe très conviviale et structurée​
* Facile à débugger​
* Obligation d'utiliser les objets ​
* Gratuit (pour vous)!​

Un second langage de programmation, le **JavaScript**, sera introduit un peu plus tard dans la session. C’est un langage reconnu dans le domaine de la programmation Web et il est de plus en plus utilisé dans d’autres contextes. 

## Mon premier programme​

Nous allons débuter un nouveau programme « Bonjour le monde ». ​
« Hello world » (traduit littéralement en français par « Bonjour le monde ») sont les mots traditionnellement écrits par un programme informatique simple dont le but est de faire la démonstration rapide de son exécution sans erreur. (Wikipedia)​

 Votre premier programme vous permettra d’écrire vos premières lignes de code et d’exécuter le code inscrit. Ce premier programme simple permettra de valider que votre environnement est fonctionnel. ​

**Sources :​**

* https://docs.microsoft.com/en-us/dotnet/core/tutorials/with-visual-studio-code​ 
* https://code.visualstudio.com/docs/languages/dotnet#_create-a-c-hello-world-app​
* https://code.visualstudio.com/docs/languages/dotnet​
* https://code.visualstudio.com/docs/languages/csharp​

Étape 1 : Démarrer Visual Studio Code​

Étape 2 : Ouvrir un dossier qui contiendra votre programme​

* Fichier - Ouvrir le dossier…​
* Choisir un emplacement approprié (par exemple, Documents / Programmation 1)​
* Créer un sous-dossier nommé BonjourLeMonde​
* Sélectionner le dossier créé​

Étape 3 : Ouvrir le terminal et initialiser votre programme​

* View -> Terminal (raccourci clavier : CTRL `)​
* Dans le terminal, écrivez la commande suivante : dotnet new console​
  
Étape 4 : Écrire le code du programme​

* Prenez un moment pour consulter le contenu présent dans le fichier Program.cs (on y reviendra!)​

* Modifiez le texte « Hello World! » Pour « Bonjour le monde! »​

Étape 5 : Démarrer l’exécution du programme ​

* Menu Exécuter > Démarrer le débogage (commande F5)​

Étape 6 : Observez le résultat!

​

​
​


​

