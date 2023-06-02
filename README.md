Comment installer le bot ?

1 - Tout d'abord veuillez installer le fichier __.zip__ sur votre ordinateur.
2 - Veuillez extraire le fichier du Winrar (sur votre bureau). Si vous n'avez pas de logiciel d'extension Winrar voici https://www.win-rar.com/start.html?&L=10
3 - Ouvrez ensuite le projet avec Visual Studio Code. Si vous n'avez pas le logiciel Visual Studio Code voici https://code.visualstudio.com
4 - Une fois le projet ouvert cliquez dans __src__ puis aller dans __config.js__. Remplissez ce qu'il faut (Token du bot, Identifiant du bot, Préfix du bot, Identifiant Owner)
5 - Une fois l'étape précèdent rempli, veuillez ouvrir un terminal soit __CRTL J__ ou en haut vous avez__Terminal__ puis cliquez sur Nouveau Terminal.
6 - Faite dans votre console `npm init --y`.
7 - Une fois l'étape précèdent faite vous devriez avoir 2 fichiers qui se sont créé un `package.json` & `package-lock.json`.
8 - Une fois fais reprenez votre terminal & faite les commandes suivantes `npm install discord.js node-superfetch fs colors @discordjs/rest dotenv` .
9 - Un dossier node-module devrait être créé ceci est parfaitement normal.
10 - Réouvrez votre terminal & faite `node main.js` & profité pleinement de votre bot.
 

Puis-je rencontrais des erreurs ?

Oui, vous pouvez par une mauvaise attention de votre part.

Si vous oubliez une description dans votre SlashCommands une erreur de ce type : description[BASE_TYPE_REQUIRED]: This field is required apparaît.
__Étape à suivre :__

1 - Vérifié qu'il y a bien une description sur votre commande.
2 - Vérifiés toute vos SlashCommands & vérifier leurs descriptions.


Si vous oubliez un titre dans votre SlashCommands une erreur de ce type : TypeError: slashCommand.split is not a function apparaît.
__Étape à suivre :__

1 - Vérifié qu'il y a bien un nom sur votre commande.
2 - Vérifiés toute vos SlashCommands & vérifier leurs noms.

Si vous avez un nom de commande dupliquer dans une autre SlashCommands une erreur de ce type : 1[APPLICATION_COMMANDS_DUPLICATE_NAME]: Application command names must be unique apparaît.
__Étape à suivre :__

1 - Vérifiés toute vos SlashCommands & vérifier leurs noms, si il ne sont pas les mêmes.


Pour toute question relative au développement voici le serveur support : https://discord.gg/badprotect
