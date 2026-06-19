# 🔐 Connexion & sécurité

EMPIRE Survival fonctionne en **offline mode** (comptes crackés autorisés). Pour protéger ton pseudo, le serveur utilise **AuthMe** : à ta première arrivée, tu crées un mot de passe, puis tu te connectes avec à chaque session.

## Première connexion

1. Connecte-toi avec ton pseudo sur l'IP du serveur.
2. Enregistre ton mot de passe :
   ```
   /register <motdepasse> <motdepasse>
   ```
3. C'est fait ! Ton pseudo est désormais protégé.

## Connexions suivantes

À chaque retour sur le serveur :
```
/login <motdepasse>
```

{% hint style="warning" %}
Tant que tu n'es pas connecté (`/login`), tu ne peux ni bouger ni parler. C'est normal : c'est la protection anti-vol de pseudo.
{% endhint %}

## Gérer ton mot de passe

| Commande | Description |
|----------|-------------|
| `/register <mdp> <mdp>` | Créer ton compte (1re fois) |
| `/login <mdp>` | Te connecter |
| `/changepassword <ancien> <nouveau>` | Changer ton mot de passe |

{% hint style="info" %}
Les sessions durent **30 minutes** : si tu te reconnectes rapidement (même IP), tu n'auras pas à retaper `/login`.
{% endhint %}
