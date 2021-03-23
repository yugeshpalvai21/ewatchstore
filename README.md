### Getting Started

##### Generating SSH keys on Local Machine

```
 > ssh-keygen
 > cat ~/.ssh/id_rsa.pub

 ###### COPY OUT PUT VALUE
 ###### PASTE IT IN Github Home > Settings > Add SSH Keys

 > git clone <ssh_repo_url>

 ### IF you Already set Origin to HTTPS and want to change to SSH

 > git remote set-url origin <ssh_repo_url>

 > git clone or > git push
```