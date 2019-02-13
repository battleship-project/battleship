## Pré-requis pour javaFX

### 1. Installation du JRE 8 (Java Runtime Environment)

* Installation à partir de la source apt depuis linux:

```shell
sudo apt install openjdk-8-jre
```

* Configuration du JRE 8 par défaut:

```shell
sudo update-alternatives --config java
```

> Sélectionner la JRE 8 en saissant le chiffre correspondant.

### 2. Installation du JDK 8 (Java Developpment Kit)

* Installation à partir de la source apt depuis linux:

```shell
sudo apt install openjdk-8-jdk
```

* Configuration du JDK 8 par défaut:

```shell
sudo update-alternative --config java
```

> Sélectionner la JDK 8 en saissant le chiffre correspondant.

### 3. Installation de SceneBuilder

* Télécharger et installer la dernière version de SceneBuilder depuis le lien ci-dessous:

> https://gluonhq.com/products/scene-builder/#download

* Indiquer le chemin d'installation de SceneBuilder depuis idea

> Settings > Languages & Frameworks > JavaFX



## Memento Git

> IMPORTANT: ne syncronisez que les sources de votre projet ! (surtout pas le .idea et autres)

### 1. Initialisation

* Initialisation du repertoire courant comme repository Git

```shell
git init
```

* Faire le lien avec le repository distant:

```shell
git remote add origin <https://mon.url.git
```

### 2. Utilisation

#### Sélection des fichiers à versionner

* Ajout d'un fichier au versionnage:

```shell
git add <monfichier.extension>
```

* Ajout de tous les fichiers du projet au versionnage:

```shell
git add -A
```

#### Ajout d'un commit

```shell
git commit -am "description de la version"
```

#### Téléverser votre version vers le serveur

```shell
git push origin master
```

#### Télécharger la version du serveur vers votre machine

```shell
git pull -u origin master
```

