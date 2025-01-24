# Checkpoint1
## exercice 1
### Creation de patition de 6G type ext4 ###
#### **fdisk /dev/sdb** #### 

####  **mkfs.ext4 /dev/sdb1** #### 
![Logo Markdown en blanc sur fond bleu](!
[
Logo Markdown en blanc sur fond bleu
](
https://www.markdownguide.org/assets/images/markdown-guide-og.jpg
)
)
x### Creation de patition swap ###
#### *fdisk /dev/sdb* ####
#### *mkswap /dev/sdb2* ####
#### *swapon /dev/sdb2* ####

### Montage ###
#### *blkid /dev/sdb* ####
#### *nano /etc/fstab* #### 
#### *mkdir /mnt/data* ####
#### POUR TESTER L AUTOMATIQYE ####
#### *mount –a* ####





