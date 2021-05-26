author: Alexandre Barczyk
summary: Tutoriel application native JAVA
id: unique-codelab-identifier-123456789
categories: codelab,markdown
environments: Web
status: Published

# TUTORIEL APPLICATION NATIVE JAVA



## Installation Android Studio
Duration: 0:15:00

Vous pouvez télécharger Android Studio 4.2.1 depuis [cette page](https://developer.android.com/studio/).

Si vous ne disposez d'aucun JDK, ce n'est pas grave, tout vient avec le téléchargement d'Android Studio.

Voici les quelques étapes que vous serez menés à réaliser:

* Accédez à la page de téléchargement d'Android Studio et suivez les instructions pour télécharger et installer Android Studio.
* Acceptez les configurations par défaut pour toutes les étapes et assurez-vous que tous les composants sont sélectionnés pour l'installation.
* Une fois l'installation terminée, l'assistant de configuration télécharge et installe des composants supplémentaires, y compris le SDK Android. Soyez patient, car ce processus peut prendre un certain temps, selon la vitesse de votre connexion Internet.
* Enfin, Android Studio démarre et vous êtes prêt à créer votre premier projet.

Negative
: **Dépannage**: si vous rencontrez des problèmes avec votre installation, consultez [les notes de version](https://developer.android.com/studio/releases) d'Android Studio ou [la section de résolution de problème](https://developer.android.com/studio/troubleshoot) d'Android Studio.



## Création du projet

Dans cette étape, vous allez créer un nouveau projet Android pour votre première application. Cette application simple affiche la chaîne "Hello World" sur l'écran d'un appareil virtuel ou physique Android. Pour éviter des potentiels problèmes, nous utiliserons dans ce tutoriel l'appareil émulé par Android Studio.

Voici à quoi ressemblera l'application terminée:

<img src="./asset/LadyDiaryHome.png" width="250"/>

### **Ce que vous apprendrez**

- Comment créer un projet dans Android Studio.
- Comment créer un appareil Androaid émulé.
- Comment exécuter votre application sur l'émulateur.



### **Étape 1: Créer un nouveau projet**

1. Ouvrir Android Studio
2. Dans la boîte de dialogue Bienvenue dans Android Studio, cliquez sur Démarrer un nouveau projet Android Studio.
3. Sélectionnez Activité de base (pas la valeur par défaut). Cliquez sur Suivant.<img src="/Users/alexandrebarczyk/Documents/ECOLE/LA2/Mobile/asset/New_activity.png" width="600" />
4. Donnez à votre application un nom tel que **Ma première application avec Alexandre qui va être superbe**<img src="/Users/alexandrebarczyk/Documents/ECOLE/LA2/Mobile/asset/New_project.png" width="600" />
5. Assurez-vous que le **langage** est défini sur **Java ** (et pas Kotlin).
6. Laissez les valeurs par défaut pour les autres champs.
7. Cliquez sur **Terminer**.

Après ces étapes, Android Studio :

- Crée un dossier pour votre projet Android Studio appelé **Ma première application avec Alexandre qui va être superbe**. C'est généralement dans un dossier appelé **AndroidStudioProjects** sous votre répertoire personnel (cmd+shift+H sur mac).
- Construit votre projet (cela peut prendre quelques instants). Android Studio utilise [Gradle ](https://gradle.org/)comme système de construction. Vous pouvez suivre la progression de la construction en bas de la fenêtre Android Studio.
- Ouvre l'éditeur de code affichant votre projet.