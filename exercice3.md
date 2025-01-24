# Checkpoint1
## exercice 3
### 1. La commande qui permet d"afficher la liste des utilisateus ###
#### *cat /etc/passwd* #### 
![listeUser ](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/USER.png)

### 2. La commande de xhanger les droits au fichier myfile rwxr--r-- ###
#### *chmod 744 myfile* #### 

### 3. la différence entre variables local et variables d'environnement en bash script ###
#### variables local celles qui n'existent que dans les limites du shell dans lequel elles ont été créées ####
#### variables d'environnement  qui sont héritées par les shells et/ou les processus enfants ####


### 4. la commande if dans bash script ###
#### structure conditionnelle "if" en Bash signifie que le code sera exécuté uniquement si la condition testée est vraie. Si elle est fausse, aucune action spécifique sera exécutée. ####

#### exemple: Vérifier si le répertoire existe ####
### *if [ ! -d "$1" ]; then
	echo "Erreur : Le répertoire $1 n'existe pas."
	exit 1
fi* ###

