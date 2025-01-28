# Checkpoint1
## exercice 3
### 1. La commande qui permet d"afficher la liste des utilisateus 
   *cat /etc/passwd*  
![listeUser ](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/USER.png)

### 2. La commande de xhanger les droits au fichier myfile rwxr--r-- 
   *chmod 744 myfile*  

### 3. la différence entre variables local et variables d'environnement en bash script ###
	 variables local celles qui n'existent que dans les limites du shell dans lequel elles ont été créées ####
	 variables d'environnement  qui sont héritées par les shells et/ou les processus enfants ####


### 4. la commande if dans bash script ###
#### structure conditionnelle "if" en Bash signifie que le code sera exécuté uniquement si la condition testée est vraie. Si elle est fausse, aucune action spécifique sera exécutée. ####

#### exemple: Vérifier si le répertoire existe ####
###  Eexmple :
        if [ ! -d "$1" ]; then
	echo "Erreur : Le répertoire $1 n'existe pas."
	exit 1
 	fi

### 5. le script est :
   echo 'Malgre le prix élevé de 100$ , il a dit "Bonjour !" au vendeur :
   - "Bonjour est-ce que ce clavier fonctionne bien ?"
   - "Evidemment ! On peut tout ecrire avec, que ce soit des pipe | ou bien des backslash \\ !"
   - "Même des tildes ~ ?"
   - "Evidement !" '
       
### 6. Pour mettre en avant le processus gedit, tu peux utiliser la commande suivante dans le terminal : 
    fg %1 


### 7. Materiel réseaux sur la cauche 2 C'est switch
    Matériel réseau de la cauxhe 3 c'est Rrouteur
    La couche 2 commute les trames Ethernet en fonction des adresses MAC 
    la couche 3 transfère les paquets IP à l'aide des adresses réseau*

#### 8. les commandes bash vers powershell
	cd  | Set-Location ou cd
  	cp   | Copy-Item    
 	 mkdir| New-Item -ItemType Director
 	ls   | Get-ChildItem  ou ls

### 9. payload : C'est la charge utile
 	le PAYLOAD = la charge utile (ou donnée utile) qui est envoyée dans la 
 	trame. Le payload est encapsulé dans une trame, qui contient diverses 
	 informations : la fréquence utilisée, le timestamp, etc..

#### 10. CIDR
	CIDR Pour simplifier l’écriture des masques de sous réseau, on écrit simplement le nombre de bits à 1 précédé d’un /.


