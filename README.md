# Nom du projet
Ce projet est une application Android simple qui utilise AsyncTask pour effectuer des tâches en arrière-plan.

## Structure du projet
Le projet est structuré comme suit :

- `app/` : contient le code source de l'application, les ressources, les règles ProGuard et le fichier de configuration Gradle.
- `gradle/` : contient les fichiers de configuration de Gradle.
- `.idea/` : contient les fichiers de configuration spécifiques à IntelliJ IDEA.
- `.gitignore` : spécifie les fichiers et dossiers à ignorer dans Git.
- `gradle.properties` : contient les paramètres de configuration de Gradle pour ce projet.
- `gradlew` et `gradlew.bat` : scripts pour exécuter Gradle sur Unix/Linux et Windows, respectivement.
- `settings.gradle.kts` : contient les paramètres de configuration de Gradle pour ce projet.

## Comment construire
Pour construire ce projet, exécutez le script `build` dans le fichier build.gradle.kts :

## Comment exécuter
Pour exécuter cette application, vous devez d'abord la construire, puis l'installer sur un appareil Android ou un émulateur. Vous pouvez utiliser Android Studio pour cela, ou exécuter la commande suivante dans le terminal :
    
```shell
    ./gradlew installDebug
```

## Dépendances
Ce projet utilise les dépendances suivantes :

- AndroidX : pour les fonctionnalités et les composants de l'interface utilisateur.
- Gradle : pour la gestion des dépendances et la construction du projet.
