# Politique de confidentialité · Privacy Policy — Check Pub

**Dernière mise à jour / Last updated : 20 septembre 2026 / September 20, 2026**

[🇫🇷 Français](#français) · [🇬🇧 English](#english)

---

## Français

### 1. Qui sommes-nous ?

**Check Pub** (le « Bot ») est un bot Discord de vérification et de gestion de publicités entre serveurs. Il est développé et exploité par **Check Pub Owner** (« nous »), depuis la Belgique.

- Site web : <https://checkpub.oxyde-bots.xyz>
- Serveur de support : <https://discord.gg/jshATDPGar>
- Contact : gabsamw@oxyde-bots.xyz

Nous sommes responsables du traitement des données décrites ci-dessous. Cette politique couvre le Bot. Les administrateurs des serveurs qui l'installent restent responsables de l'usage qu'ils en font auprès de leur communauté (voir §9).

### 2. En bref

- Le Bot ne lit le contenu des messages que dans les **salons de publicité configurés par les administrateurs** (et pour quelques usages listés au §4). Le contenu des autres messages est ignoré.
- Le **contenu des messages n'est ni stocké, ni journalisé** par nous.
- Nous conservons des **identifiants Discord**, des **compteurs**, des **avertissements/sanctions** saisis par le staff et la **configuration** des serveurs. Rien d'autre sur vous (ni pseudo, ni avatar, ni e-mail).
- Nous **ne vendons pas** vos données, ne faisons pas de publicité ciblée et ne créons pas de profils.
- Le Bot **n'utilise aucune intelligence artificielle** et vos données ne servent **jamais** à entraîner un modèle d'IA ou d'apprentissage automatique.

### 3. Données que nous conservons

**3.1 Configuration des serveurs.** Identifiant du serveur ; identifiants des salons et rôles configurés (salons de publicité, de vérification, de logs ; rôles staff, admin, liste blanche) ; préfixe et options activées ; textes saisis par les administrateurs (message de bienvenue, modèles d'embeds, règles d'auto-sanction) ; listes noires du serveur (identifiants d'utilisateurs, ou identifiants de serveurs avec code d'invitation, et un motif optionnel) ; statistiques du serveur (nombre de publicités reçues et vérifiées, total et par jour de la semaine).

**3.2 Compteurs et classements.** Votre **identifiant Discord** (numérique) associé à : nombre de publicités envoyées et vérifiées, de partenariats et de bumps (par serveur et au total), date de dernière action, points de classement et date du dernier bump par serveur. Ces compteurs sont affichés par les commandes `/profil` et `/leaderboard`, y compris le total sur l'ensemble des serveurs qui utilisent le Bot. Le pseudo et l'avatar affichés sont ceux que Discord fournit au moment de l'affichage ; nous ne les enregistrons pas.

**3.3 Avertissements et sanctions.** Par serveur : identifiant de l'utilisateur, identifiant de l'avertissement et motif rédigé par le staff ; sanctions automatiques appliquées (mise en sourdine, expulsion, bannissement) avec leur date de fin.

**3.4 Listes noires globales et liste de surveillance.** Gérées par notre équipe pour lutter contre les abus : identifiants d'utilisateurs et de serveurs exclus du Bot, et une liste de surveillance (« avertisseur ») associant un identifiant à un motif, qui affiche une mention d'avertissement au staff dans l'embed de vérification, sur tout serveur utilisant le Bot. L'utilisateur concerné est prévenu par message privé lorsqu'il y est ajouté et peut contester via notre serveur de support.

**3.5 Salons personnalisés.** Si la fonction `/salon-perso` est utilisée : identifiants du propriétaire du salon, du membre du staff qui l'a créé, du salon et des rôles, motif, durée et date de fin, nom du salon et texte de la publicité saisi par le staff (conservé pour pouvoir restaurer ou republier le salon).

**3.6 Ajout et retrait du Bot.** Lorsque le Bot est ajouté ou retiré d'un serveur, les informations suivantes sont publiées dans un salon privé de notre équipe : nom, identifiant, icône, date de création, nombre de membres et langue du serveur, identifiant et pseudo du propriétaire. À l'ajout, le Bot crée un lien d'invitation vers le serveur, transmis à notre équipe afin d'assurer le support et de traiter les abus, et envoie un message privé au propriétaire (remerciement et aide). Si le propriétaire est membre de notre serveur de support, un rôle d'utilisateur du Bot peut lui être attribué, puis retiré au retrait du Bot.

**3.7 Journaux techniques.** Journaux d'exécution et fichiers d'erreurs ou de limites de débit contenant des identifiants de serveurs, de salons ou d'utilisateurs concernés par une action (avertissement, blacklist, erreur…). Ils ne contiennent **jamais** le contenu des messages.

### 4. Traitements en temps réel (non conservés)

- **Contenu des messages.** Discord transmet au Bot les messages des serveurs où il est présent. Le Bot n'agit que sur : (a) les salons de publicité configurés par les administrateurs ; (b) les messages de confirmation des bots de bump (DISBOARD, DiscordTop, DiscordL, WorldBump, DiscordInvites, French.gg) ; (c) la mention du Bot et les commandes à préfixe. Dans les salons de publicité, le contenu sert à détecter les liens d'invitation, appliquer les règles du salon (description minimale, liens obligatoires…), transmettre la publicité au salon de vérification **du même serveur** et supprimer les liens expirés (contrôle toutes les 30 minutes sur les messages des 14 derniers jours). Il n'est pas enregistré dans notre base de données.
- **Codes d'invitation.** Seul le **code** (jamais le message ni son auteur) est envoyé à notre API (`api-info.oxyde-bots.xyz`), qui interroge Discord et renvoie les informations publiques de l'invitation : nom et identifiant du serveur, nombre de membres, indicateur NSFW.
- **Tournée de publicité.** Si un même utilisateur publie l'invitation d'un même serveur dans plusieurs serveurs qui utilisent le Bot, le Bot le repère en mémoire vive pendant quelques minutes. Si le serveur invité l'a activé, son staff reçoit un récapitulatif dans le salon de son choix : l'auteur (identifiant et pseudo) et les serveurs (nom et identifiant) où il a publié. Si le serveur invité utilise un bot personnalisé exploité par nous, ces informations lui sont transmises directement. Nous ne les conservons pas.
- **Messages privés envoyés par le Bot.** Uniquement : message de bienvenue (si un administrateur l'a activé), notification d'ajout à la liste de surveillance ou à une liste noire, message au propriétaire lors de l'ajout du Bot (§3.6).

### 5. Partage des données

Nous ne vendons, ne louons et ne partageons pas vos données à des fins commerciales. Elles sont accessibles :

- au **staff du serveur** concerné (informations de vérification, avertissements, statistiques) ;
- aux **membres du serveur** via `/profil` et `/leaderboard` (§3.2) ;
- à **notre équipe**, pour l'exploitation du Bot, le support et la lutte contre les abus ;
- à des **prestataires techniques** : notre hébergement (infrastructure que nous administrons) et **QuickChart** (`quickchart.io`), qui génère l'image du graphique de `/statistique week` et ne reçoit que des totaux quotidiens du serveur, sans donnée personnelle ;
- à **Discord**, plateforme sur laquelle le Bot fonctionne (la [politique de confidentialité de Discord](https://discord.com/privacy) s'applique aussi) ;
- aux autorités, si la loi nous y oblige.

### 6. Base légale (RGPD)

Nous traitons ces données sur la base de notre **intérêt légitime** à fournir le service demandé par les administrateurs de serveurs, à assurer sa sécurité et à lutter contre le spam et les abus (art. 6.1.f RGPD), et, pour les administrateurs, de l'**exécution du service** qu'ils ont installé (art. 6.1.b).

### 7. Durées de conservation

| Données | Durée |
|---|---|
| Configuration du serveur | Tant que le Bot est présent. Après son retrait, elle est conservée pour faciliter une réinstallation, et supprimée sur demande. |
| Compteurs et classements | Jusqu'à réinitialisation par le staff (`/reset-users`, `/reset-leaderboard`) ou suppression sur demande. |
| Avertissements et sanctions | Jusqu'à leur retrait ou réinitialisation par le staff (`/warn remove`, `/warn-reset`) ou suppression sur demande. |
| Listes noires et liste de surveillance | Tant que le motif subsiste ; réexamen sur demande. |
| Salons personnalisés | Jusqu'à la suppression du salon personnalisé. |
| Journaux techniques | Le temps nécessaire au débogage et à la sécurité. |
| Contenu des messages, tournée de publicité | Non conservés (traitement en mémoire, quelques minutes au maximum). |

### 8. Vos droits

Vous pouvez demander l'**accès** à vos données, leur **rectification**, leur **effacement**, la **limitation** ou l'**opposition** à leur traitement, et leur **portabilité**. Écrivez-nous à gabsamw@oxyde-bots.xyz ou ouvrez un ticket sur notre [serveur de support](https://discord.gg/jshATDPGar), en indiquant votre identifiant Discord. Nous répondons dans un délai d'un mois.

Le Bot ne traite vos messages que dans les salons de publicité : vous pouvez vous y opposer en n'y publiant pas. Vous pouvez aussi faire retirer vos compteurs de nos bases sur simple demande.

Si vous estimez que vos droits ne sont pas respectés, vous pouvez introduire une réclamation auprès de l'**Autorité de protection des données** (Belgique) : <https://www.autoriteprotectiondonnees.be>.

### 9. Administrateurs de serveurs

Les administrateurs qui installent le Bot décident des salons surveillés, des avertissements, des sanctions automatiques et du message de bienvenue. Il leur appartient d'informer leur communauté et de respecter la réglementation applicable à ces usages. Ils peuvent réinitialiser les données de leur serveur avec les commandes citées au §7, et retirer le Bot à tout moment pour mettre fin au traitement.

### 10. Sécurité

Nous appliquons des mesures raisonnables : infrastructure administrée par nos soins, accès à la base de données limité à notre équipe, secrets stockés hors du code source. Aucun système n'étant infaillible, nous ne pouvons garantir une sécurité absolue. En cas de violation de données présentant un risque pour vous, nous vous en informerons ainsi que l'autorité compétente lorsque la loi l'exige.

### 11. Mineurs

Le Bot s'adresse aux utilisateurs qui respectent l'âge minimum requis par Discord. Nous ne collectons pas sciemment de données de personnes qui ne le respectent pas ; si vous pensez que c'est le cas, contactez-nous pour les faire supprimer.

### 12. Modifications

Nous pouvons mettre à jour cette politique. La date de dernière mise à jour figure en haut du document ; les changements importants sont annoncés sur notre serveur de support.

### 13. Contact

gabsamw@oxyde-bots.xyz · [Serveur de support](https://discord.gg/jshATDPGar) · <https://check-pub.xyz>

---

## English

### 1. Who we are

**Check Pub** (the "Bot") is a Discord bot that verifies and manages advertisements between servers. It is developed and operated by **Oxyde Bots** ("we", "us") from Belgium.

- Website: <https://check-pub.xyz>
- Support server: <https://discord.gg/jshATDPGar>
- Contact: gabsamw@oxyde-bots.xyz

We are the data controller for the data described below. This policy covers the Bot. Server administrators who install it remain responsible for how they use it with their own community (see §9).

### 2. In short

- The Bot reads message content only in the **advertising channels set up by server administrators** (plus a few uses listed in §4). The content of all other messages is ignored.
- **Message content is neither stored nor logged** by us.
- We keep **Discord IDs**, **counters**, **warnings/sanctions** entered by server staff, and **server configuration**. Nothing else about you (no username, avatar or email).
- We **do not sell** your data, run targeted advertising, or build profiles.
- The Bot **uses no artificial intelligence**, and your data is **never** used to train an AI or machine-learning model.

### 3. Data we store

**3.1 Server configuration.** Server ID; IDs of configured channels and roles (advertising, verification and log channels; staff, admin and whitelist roles); prefix and enabled options; texts written by administrators (welcome message, embed presets, auto-sanction rules); server blacklists (user IDs, or server IDs with an invite code, plus an optional reason); server statistics (ads received and verified, total and per weekday).

**3.2 Counters and leaderboards.** Your numeric **Discord ID** linked to: number of ads sent and verified, partnerships and bumps (per server and overall), date of last activity, leaderboard points and last bump date per server. These counters are shown by the `/profil` and `/leaderboard` commands, including the total across all servers that use the Bot. The username and avatar displayed are those Discord provides at display time; we do not save them.

**3.3 Warnings and sanctions.** Per server: user ID, warning ID and a reason written by staff; automatic sanctions applied (timeout, kick, ban) with their end date.

**3.4 Global blacklists and watchlist.** Managed by our team to fight abuse: IDs of users and servers excluded from the Bot, and a watchlist ("avertisseur") linking an ID to a reason, which adds a warning note for staff in the verification embed on any server using the Bot. The user concerned is notified by direct message when added and can appeal through our support server.

**3.5 Personal channels.** If the `/salon-perso` feature is used: IDs of the channel owner, the staff member who created it, the channel and roles; reason, duration and end date; channel name and the ad text entered by staff (kept so the channel can be restored or re-posted).

**3.6 Adding and removing the Bot.** When the Bot is added to or removed from a server, the following is posted in a private channel of our team: server name, ID, icon, creation date, member count and locale, and the owner's ID and username. On installation, the Bot creates an invite link to the server, passed to our team to provide support and handle abuse, and sends the owner a direct message (thanks and help). If the owner is a member of our support server, a Bot-user role may be granted, and removed when the Bot is removed.

**3.7 Technical logs.** Runtime logs and error / rate-limit files containing IDs of servers, channels or users involved in an action (warning, blacklist, error…). They **never** contain message content.

### 4. Real-time processing (not stored)

- **Message content.** Discord delivers messages from the servers where the Bot is present. The Bot only acts on: (a) advertising channels configured by administrators; (b) confirmation messages from bump bots (DISBOARD, DiscordTop, DiscordL, WorldBump, DiscordInvites, French.gg); (c) mentions of the Bot and prefix commands. In advertising channels, content is used to detect invite links, apply the channel's rules (minimum description, link required…), forward the ad to the verification channel **of the same server**, and remove expired links (checked every 30 minutes over messages from the last 14 days). It is not saved in our database.
- **Invite codes.** Only the invite **code** (never the message or its author) is sent to our API (`api-info.oxyde-bots.xyz`), which queries Discord and returns the invite's public information: server name and ID, member count, NSFW flag.
- **Ad tours.** If one user posts the invite of the same server in several servers using the Bot, the Bot notices it in memory for a few minutes. If the invited server enabled it, its staff receives a recap in the channel of its choice: the author (ID and username) and the servers (name and ID) where they posted. If the invited server uses a custom bot operated by us, this information is sent to it directly. We do not keep it.
- **Direct messages sent by the Bot.** Only: welcome message (if an administrator enabled it), notification of addition to the watchlist or a blacklist, and the message to a server owner when the Bot is added (§3.6).

### 5. Sharing

We do not sell, rent or share your data for commercial purposes. It is accessible to:

- the **staff of the relevant server** (verification details, warnings, statistics);
- **members of the server** through `/profil` and `/leaderboard` (§3.2);
- **our team**, to operate the Bot, provide support and fight abuse;
- **technical providers**: our hosting (infrastructure we administer) and **QuickChart** (`quickchart.io`), which renders the `/statistique week` chart image and only receives a server's daily totals, with no personal data;
- **Discord**, the platform the Bot runs on ([Discord's privacy policy](https://discord.com/privacy) also applies);
- authorities, where the law requires it.

### 6. Legal basis (GDPR)

We process this data based on our **legitimate interest** in providing the service server administrators asked for, keeping it secure and fighting spam and abuse (Art. 6(1)(f) GDPR), and, for administrators, the **performance of the service** they installed (Art. 6(1)(b)).

### 7. Retention

| Data | Duration |
|---|---|
| Server configuration | While the Bot is present. After removal it is kept to ease reinstallation, and deleted on request. |
| Counters and leaderboards | Until reset by staff (`/reset-users`, `/reset-leaderboard`) or deleted on request. |
| Warnings and sanctions | Until removed or reset by staff (`/warn remove`, `/warn-reset`) or deleted on request. |
| Blacklists and watchlist | As long as the reason applies; reviewed on request. |
| Personal channels | Until the personal channel is deleted. |
| Technical logs | As long as needed for debugging and security. |
| Message content, ad tours | Not stored (in-memory processing, a few minutes at most). |

### 8. Your rights

You may request **access** to your data, its **rectification**, **erasure**, **restriction** or **objection** to its processing, and its **portability**. Email us at gabsamw@oxyde-bots.xyz or open a ticket on our [support server](https://discord.gg/jshATDPGar), including your Discord ID. We reply within one month.

The Bot only processes your messages in advertising channels: you can object by not posting there. You can also have your counters removed from our databases on simple request.

If you believe your rights are not respected, you may lodge a complaint with the **Data Protection Authority** (Belgium): <https://www.autoriteprotectiondonnees.be>.

### 9. Server administrators

Administrators who install the Bot decide which channels are monitored, which warnings and automatic sanctions apply, and the welcome message. They are responsible for informing their community and complying with the rules that apply to these uses. They can reset their server's data with the commands listed in §7, and remove the Bot at any time to end processing.

### 10. Security

We apply reasonable measures: infrastructure administered by us, database access limited to our team, secrets kept out of the source code. No system is infallible, so we cannot guarantee absolute security. If a data breach presents a risk to you, we will notify you and the competent authority where the law requires it.

### 11. Minors

The Bot is intended for users who meet Discord's minimum age. We do not knowingly collect data from anyone who does not; if you believe this happened, contact us so we can delete it.

### 12. Changes

We may update this policy. The last-updated date is shown at the top; significant changes are announced on our support server.

### 13. Contact

gabsamw@oxyde-bots.xyz · [Support server](https://discord.gg/jshATDPGar) · <https://check-pub.xyz>
