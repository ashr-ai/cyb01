# SSH Hardening

Mission : Durcir SSH sur Ubuntu Server

> Étant donné que nous avons déjà créé une paire de clés SSH, nous allons sauter cette étape

Premièrement, j'ai modifié `/etc/ssh/sshd_config` pour appliquer ces paramètres :
```
PermitRootLogin no
PasswordAuthentication no
MaxAuthTries 3
LoginGraceTime 20
```

Deuxièmement, j'ai redémarré le service SSH et vérifié que la connexion fonctionne toujours avec ces commandes :
```
sudo systemctl restart ssh
ssh ashr-ai@10.10.44.20
```
Cependant lorsque je me suis connecté, j'ai reçu un message d'avertissement que je me faisais potentiellement attaqué (*man-in-the-middle*). Cela me confirme que la connexion fonctionne puisque c'est moi qui ai porté des modifications à la configuration SSH.

Pour finir, j'ai tenté une connexion par mot de passe pour confirmer qu'elle est refusée et le rendu final était *host key verification failed.*
```
ssh -o PreferredAuthentications=password ashr-ai@10.10.44.20
```

Mission réussi !