# Checkpoint1
## exercice 1
### Creation de patition de 6G type ext4 ###
#### **fdisk /dev/sdb** #### 
![La partition avec le type ext4](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/partition.png)

### la patition de type ext4 ###
####  **mkfs.ext4 /dev/sdb1** #### 
![La partition avec le type ext4](https://github.com/KAOUTARBAH/Checkpoint1/blob/main/partition%20disk%20ext4.png)

### Creation de patition swap ###
#### *fdisk /dev/sdb* ####
#### *mkswap /dev/sdb2* ####
#### *swapon /dev/sdb2* ####

### Montage ###
#### *blkid /dev/sdb* ####
#### *nano /etc/fstab* #### 
#### *mkdir /mnt/data* ####
#### POUR TESTER L AUTOMATIQYE ####
#### *mount –a* ####





