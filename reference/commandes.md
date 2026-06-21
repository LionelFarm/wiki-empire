# 📜 Toutes les commandes

La liste complète des commandes joueur d'EMPIRE Survival, par catégorie.

---

## 🔐 Compte & connexion

| Commande | Description |
|----------|-------------|
| `/register <mdp> <mdp>` | Créer ton compte (1re connexion) |
| `/login <mdp>` | Te connecter |
| `/changepassword <ancien> <nouveau>` | Changer ton mot de passe |

---

## 🎨 Skin

| Commande | Description |
|----------|-------------|
| `/skin <pseudo_mojang>` | Appliquer le skin d'un compte Minecraft |
| `/skin clear` | Revenir au skin par défaut |
| `/skin update` | Forcer la mise à jour de ton skin |

---

## 🏠 Bases & déplacement

| Commande | Description |
|----------|-------------|
| `/sethome` | Définir ta base (1 seule par défaut) |
| `/sethome <nom>` | Définir une base nommée (VIP et +) |
| `/home` | Te téléporter à ta base |
| `/home <nom>` | Te téléporter à une base nommée |
| `/delhome` | Supprimer ta base |
| `/spawn` | Retourner au spawn |
| `/tpa <joueur>` | Demander à te téléporter chez un joueur |
| `/tpaccept` | Accepter une demande de TP |
| `/back` | Revenir à ta position précédente |
| `/warp` | Liste des zones publiques |

{% hint style="warning" %}
En **combat PvP**, les téléportations (`/home`, `/spawn`, `/tpa`, `/back`) sont **bloquées pendant 30 secondes** après le dernier échange de coups.
{% endhint %}

---

## 💰 Économie

| Commande | Description |
|----------|-------------|
| `/bal` | Voir ton solde |
| `/pay <joueur> <montant>` | Payer un joueur |
| `/baltop` | Classement des plus riches |
| `/ah` | Hôtel des ventes entre joueurs |

---

## ⚔️ Factions

Toutes les commandes de faction commencent par `/f` :

| Commande | Description |
|----------|-------------|
| `/f create <nom>` | Créer une faction |
| `/f invite <joueur>` | Inviter un joueur |
| `/f join <faction>` | Rejoindre une faction |
| `/f leave` | Quitter sa faction |
| `/f kick <joueur>` | Exclure un membre |
| `/f info` | Infos sur ta faction |
| `/f list` | Liste des factions |
| `/f members` | Voir les membres |
| `/f claim` | Revendiquer le chunk actuel |
| `/f unclaim` | Libérer un chunk |
| `/f sethome` | Définir la base de faction |
| `/f home` | Aller à la base de faction |
| `/f ally <faction>` | Proposer une alliance |
| `/f enemy <faction>` | Déclarer un ennemi |
| `/f map` | Carte des territoires |
| `/f chat` | Basculer en chat de faction |
| `/f wilderness` | Se téléporter dans la nature |

---

## 🎯 Primes

| Commande | Description |
|----------|-------------|
| `/bounty` | Ouvrir le menu des primes |
| `/bounty add <joueur> <montant>` | Mettre une prime sur un joueur |
| `/bounty search <joueur>` | Voir les primes sur un joueur |
| `/bounty track <joueur>` | Pister un joueur mis à prix |

---

## ⚔️ RPG

| Commande | Description |
|----------|-------------|
| `/class` | Changer de classe *(VIP, VIP+ et VIP MAX uniquement)* |
| `/skills` | Ouvrir l'arbre de compétences |
| `/skilltrees` | Arbres de talents |
| `/profile` | Voir ton profil RPG (stats, niveau, classe et **niveaux de metiers**) |
| `/attributes` | Voir et gérer tes attributs |
| `/quests` | Ouvrir le menu des quêtes |
| `/party invite <joueur>` | Inviter quelqu'un dans ton groupe |
| `/party leave` | Quitter ton groupe |
| `/friends` | Gérer ta liste d'amis |
| `/guild` | Guilde |
| `/equipement` | Ouvrir l'inventaire RPG *(alias : `/eq`, `/equip`, `/inv`)* |
| `/relique` | Ouvrir la Forge Mystique (reliques & fragments) |

---

## 🎁 Progression & récompenses

| Commande | Description |
|----------|-------------|
| `/bp` | Ouvrir le Battle Pass |
| `/rewards` | Ouvrir les récompenses journalières |

---

## 💬 Social

| Commande | Description |
|----------|-------------|
| `/msg <joueur> <message>` | Envoyer un message privé |
| `/r <message>` | Répondre au dernier message privé |

---

{% hint style="info" %}
Les commandes staff/admin ne sont pas listées ici. Certaines commandes dépendent de ton **grade** (voir [Grades & permissions](../gameplay/grades.md)).
{% endhint %}
