# AFKZones

AFKZones est un plugin Minecraft pour serveurs Paper 1.20.2+ permettant de créer des **zones AFK protégées**.  
Lorsqu'un joueur entre dans une zone AFK, il devient invincible, reçoit un message, et son pseudo passe en `[AFK]`.  
Quand il quitte la zone, tout revient à la normale.

---

## ✨ Fonctionnalités

- ✅ Définition d'une zone AFK avec `/afkzone set`
- ✅ Suppression de la zone avec `/afkzone remove`
- ✅ Joueurs invincibles dans la zone
- ✅ Préfixe `[AFK]` et pseudo grisé
- ✅ Messages personnalisables (entrée/sortie)
- ✅ Rayon configurable
- ✅ Compatible Paper 1.20.2 et Java 17

---

## 🧪 Commandes

| Commande              | Description                                 | Permission         |
|-----------------------|---------------------------------------------|---------------------|
| `/afkzone set`        | Définit la zone AFK à votre position        | `afkzone.manage`    |
| `/afkzone remove`     | Supprime la zone AFK                        | `afkzone.manage`    |

---

## ⚙️ Configuration (`config.yml`)

```yaml
radius: 10.0
enter-message: "&7Vous êtes maintenant en mode AFK. Vous ne pouvez plus subir de dégâts."
leave-message: "&7Vous n'êtes plus AFK. Vous pouvez de nouveau être attaqué."

