---
description: Le plugin roles réactions
---

# Roles Réactions

L'un des premiers plugins que j'ai ajouté au bot, c'est le plugin Rôles Réactions, car c'est une des fonctionnalités que les gens aiment bien.  
Pour configurer les roles réactions, il faut utiliser la commande  
`/reactions [new/remove/list] [nom_reaction] [salon(ID ou mention)] [messageID] [emoji] [role(ID ou mention)]`

Tout d'abord, en écrivant **/reactions list** vous obtiendrez la liste des réactions définis.

![](https://github.com/kewanfr/StarGamingDocs/tree/1a5963a519c207a7566a5c0847feb25a17f38957/.gitbook/assets/reactions.png)

⚠️Afin de pouvoir récupérer l'ID du message de la réaction, il faut d'abord activer le mode développeur. Pour cela, allez dans les paramètres utilisateur, puis **Apparence**, et enfin activer le **mode développeur**.

Vous pouvez désormais cliquer droit sur votre message puis copier l'identifiant.

![](https://github.com/kewanfr/StarGamingDocs/tree/1a5963a519c207a7566a5c0847feb25a17f38957/.gitbook/assets/copy-id.png)

Ensuite, il faut créer votre réaction !  
Nous allons faire un exemple de rôle réaction de règlement.  
Nous allons donc exécuter **`/reactions new reglement #📜╏reglement 711980938384638043 :white_check_mark: @Membres ✅`**  
Une réaction va automatiquement s'ajouter à votre message et vous allez pouvoir la cocher et décocher pour obtenir votre rôle !

Les utilisateurs vont recevoir un message lors de l'ajout d'un réaction, vous pouvez le changer via **/settings set reactionAddMessage**. Si vous souhaitez activer ce même message mais lorsque vous retirer une réaction, la propriété à changer est reactionRemoveMessage.

## ⚠️Nombres maximum de réactions

Selon le type de votre serveur, vous pouvez configurer un nombre limité de roles réactions.  
Nous avons fixés ces valeurs, elles peuvent être amenés à changer selon vos suggestions !

| Type de serveur | Nombre maximal de rôles réactions |
| :--- | :--- |
| Normal | 5 |
| Partenaire | 10 |
| Booster | 15 |
| Premium | 20 |
| Premium VIP | 40 |

