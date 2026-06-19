# 🎯 Primes (têtes mises à prix)

Mets la tête d'un joueur à prix, et celui qui le tue empoche la récompense ! Système géré par **BountyRedux**.

## Commandes

| Commande | Description |
|----------|-------------|
| `/bounty` | Ouvrir le menu des primes |
| `/bounty add <joueur> <montant>` | Mettre une prime sur un joueur |
| `/bounty search` | Voir les primes actives |
| `/bounty track <joueur>` | Pister un joueur mis à prix |

## Comment ça marche ?

1. Tu mets une prime sur un joueur avec `/bounty add <joueur> <montant>` (l'argent est retiré de ton solde).
2. La prime apparaît dans la liste publique (`/bounty`).
3. **Le joueur qui tue la cible encaisse automatiquement la prime.**

{% hint style="info" %}
La prime minimale est de **100 $**. Plusieurs joueurs peuvent ajouter à la même prime : le montant cumulé grimpe !
{% endhint %}

{% hint style="warning" %}
Si **ta** tête est mise à prix, tu deviens une cible pour tout le serveur. Utilise `/bounty track` pour savoir qui chasser… ou pour repérer qui te chasse.
{% endhint %}
