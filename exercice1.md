# Checkpoint1
## exercice 1
### Creation de patition de 6G type ext4 ###
#### **fdisk /dev/sdb** #### 
![La partition sdb](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/partition.png)

### la patition de type ext4 ###
####  **mkfs.ext4 /dev/sdb1** #### 
![La partition avec le type ext4](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/partition%20disk%20ext4.png)

### Creation de patition swap ###
#### *fdisk /dev/sdb* ####
#### *mkswap /dev/sdb2* ####
#### *swapon /dev/sdb2* ####
![La partition swap](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/swap.png)

### Montage automatique  ###
#### *blkid /dev/sdb* ####
### récuper le UUID ###
![UUID](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/uuid.png)

### Entrer dans le fichier /etc/fstab ###
#### *nano /etc/fstab* #### 
![UUID](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/fstab.png)
#### Creer le fichier  /mnt/data ####
#### *mkdir /mnt/data* ####
#### POUR TESTER  le montage automatique ####
#### *mount –a* #### 
![UUID](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/montage.png)






