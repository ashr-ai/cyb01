# Comparaison de gestionnaires de mot de passe

## Gestionnaire 1 : **NordPass**

NordPass est un gestionnaire de mot de passe généré par la compagnie Nord Security créée en 2019. Elle offre deux versions: Business et Personnel.

### Business

Ce format offre des solutions adaptées à des équipes et entreprises. Il y a un contrôle d'administration où est-ce que l'admin peut gérer les droits d'accès, activer l'authentification 2FA et consulter les journaux d'activité. Elle possède aussi une intégration RH : lorsqu'un employé quitte l'entreprise, ses mots de passe professionnels peuvent être révoqués et réassignés. Un avantage aussi est que chaque compte Business inclut un compte Personnel gratuit pour chaque employé.

### Personnel

Conçu entre 1 à 6 personnes, permet de stocker mots de passe, cartes bancaires et notes sécurisées sur un nombre illimité d'appareils.

### Tarifs

Les prix varient entre $2,49 à $7,99 pour Business (Abonnement 1 mois) et entre $0 à $4,59 pour Personnel (abonnement 1 an)

### Autres informations

Depuis 2019, la compagnie n'a jamais subi de fuite de données ni de piratage de ses serveurs. Ils utilisent l'algorithme de chiffrement **xChaCha20** qui génère un keystream combiné avec du plain text bit par bit pour produire le texte chiffré. Nord Security divulgue très rarement le nom de ses clients, mais possède une très forte notoriété. Son siège social se trouve en Amsterdam au Pays-Bas, mais son campus principal est en Lituanie dans la *Cyber City* et sa section juridique au Panama. Le Panama est un paradis pour la vie privée. Il n'oblige pas les entreprises de garder des historiques de données et n'aide pas les agences d'espionnage mondiales. L'Europe apporte en plus la loi GPDR qui punit sévèrement les abus.


## Gestionnaire 2 : **1Password**

1Password a été développé par AgileBits Inc. Ce logiciel date depuis 2006 lorsqu'ils ont sorti leur première version bêta qui était seulement disponible sur Mac. Elle offre également deux versions : Business et Personnel.

### Business

1Password Business possède des fonctionnalités similaires à NordPass avec des fonctionnalités en surplus :
- Business possède une *secret key* qui est une clé de sécurité
- Des comptes invités gratuits pour les personnes extérieures à l'entreprise
- Une suite développeur qui possède des outils comme un gestionnaire de clés SSH, une interface en ligne de commande, etc.
- *Device Trust* : Avant de laisser un employé ouvrir son coffre-fort de mots de passe d'entreprise, 1Password peut vérifier si son ordinateur est à jour, si son pare-feu est activé et si son disque dur est chiffré. Si l'appareil de l'employé n'est pas sécurisé, l'accès lui est bloqué.
- Business offre un abonnement Families gratuit pour 5 personnes à chaque employé

### Personnel

Comparé à NordPass, 1Password te permet de stocker jusqu'à 1 Go de fichiers. Aussi il y a le mode Voyage, une fonction qui permet de marquer certains de ses coffres-forts comme *sûrs pour le voyage* et de masquer temporairement tous les autres de ses appareils avant de traverser une frontière. De ce sens, si quelqu'un oblige l'utilisateur à déverrouiller son téléphone, les coffres masqués sont totalement invisibles et introuvables sur l'appareil. Ils réapparaissent en un clic dès que vous désactivez le mode depuis le site web sécurisé.

### Tarifs

entre $5 à $7 par mois pour Personal, $24,95/mois pour Teams (10 utilisateurs) et $9,99/mois par utilisateur pour Business

### Autres informations

1Password n'a jamais subi de fuite de données de coffres-forts. En 2023, un pirate avait réussi à s'introduire dans leur environnement d'administration interne, mais l'attaque a été bloquée immédiatement et aucune donnée utilisateur a été consulté. En raison de sa popularité, 1Password est une cible pour les campagnes d'hameçonnage. Ses clients importants sont IBM, Slack, PagerDuty, GitLab, Under Armour et Intercom. Son algorithme de chiffrement est AES-256, qui chiffre par bloc à la place de bit par bit. Son bureau-chef est situé à Toronto, au Canada. Le Canada fait partie d'une alliance de surveillance internationale (*Five Eyes*). Le gouvernement peut légalement demander des comptes.

