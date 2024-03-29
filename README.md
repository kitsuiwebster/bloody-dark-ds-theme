# Bloody Dark Mode Discord Theme

A Dark-Mode Discord theme for BetterDiscord users 

## How To Install BetterDiscord

### Windows

Download and install BetterDiscord: https://betterdiscord.app/

### Linux

Install betterdiscordctl with curl

```txt
curl -O https://raw.githubusercontent.com/bb010g/betterdiscordctl/master/betterdiscordctl
chmod +x betterdiscordctl
sudo mv betterdiscordctl /usr/local/bin
```

You can then keep `betterdiscordctl` up to date with this command:
```
sudo betterdiscordctl self-upgrade
```

Install BetterDiscord

Replace `[COMMAND]` with `install` to install BD for the first time,
`reinstall` to reinstall BD after a Discord update,
or `uninstall` to uninstall an existing installation.

- For Stable

```
betterdiscordctl [COMMAND]
```

- For PTB

```
betterdiscordctl --flavor PTB [COMMAND]
```

- For Canary

```
betterdiscordctl --flavor Canary [COMMAND]
```

- For Snap

```
betterdiscordctl --d-install snap [COMMAND]
```

- For Flatpak

```
betterdiscordctl --d-install flatpak [COMMAND]
```

## How to add 'Bloody Dark Mode Discord Theme' to your Discord client

Once BetterDiscord is installed:

> Reload your Discord client

> Copy the CSS code

> Go to the Discord settings, scroll until the 'Custom CSS' tab

> Paste into the editor window

## License

See LICENSE.md for more details

## Previews

![preview](./previews/preview1.png)

![preview](./previews/preview2.png)

## Credits

#### [BetterDiscord](https://github.com/Jiiks/BetterDiscordApp) by Jiiks

#### [Bandaged BD](https://github.com/rauenzi/BetterDiscordApp) by Zerebos (rauenzi)

#### [betterdiscordctl](https://github.com/bb010g/betterdiscordctl) by bb010g

Here is the CSS theme source code:

```css

/*
 * @name Bloody Dark Mode Discord Theme
 * @author Raphaël Martin | Kitsui#8258
 * @description A dark mode discord theme for BetterDiscord users
 * @source https://gitlab.com/kitsuiwebster/bloody-dark-mode-ds-theme

 * How to proceed:
1. Download and install BetterDiscord: https://betterdiscord.app/
2. Reload Discord
3. Go to the Discord settings, scroll until the 'Custom CSS' tab
4. Copy this code snippet and paste it in the editor window 

*/


 @import url("https://fonts.googleapis.com/css2?family=Rajdhani");

 :root {
   --background-primary: linear-gradient(
     180deg,
     rgba(23, 0, 5, 0.75) 10%,
     rgba(0, 0, 0, 1) 65%
   );
   --background-secondary: linear-gradient(
     180deg,
     rgba(23, 0, 5, 0.75) 10%,
     rgba(0, 0, 0, 1) 65%
   );
   --font-primary: "Rajdhani";
   --primary-text-color: lightgray;
 }
 
 /*
 -------
 TOP BAR
 -------
 */
 
 .title-31SJ6t {
   background: black;
   box-sizing: content-box;
 }
 
 .toolbar-3_r2xA {
   margin-right: 1rem;
 }
 
 .base-ZDDK0g,
 #app-mount .iconWrapper-2awDjA svg {
   color: var(--primary-text-color);
 }
 
 .children-3xh0VB .topic-11NuQZ {
   color: var(--primary-text-color);
 }
 
 .searchBar-jGtisZ {
   background: #180000;
   border-radius: 4px;
 }
 
 /*
 ------------
 SERVER TITLE
 ------------
 */
 
 .headerContent-2SNbie {
   color: var(--primary-text-color);
   font-family: var(--font-primary);
 }
 
 #app-mount .header-3OsQeK {
   background: black;
 }
 
 /*
 ----------------------
 LEFT SIDE CHANNEL LIST
 ----------------------
 */
 
 .content-1gYQeQ {
   background: #000000;
 }
 
 .wrapper-1S43wv .name-3BUDLf,
 .icon-2W8DHg {
   color: var(--primary-text-color);
 }
 
 .children-3MeUvj svg {
   color: var(--primary-text-color);
 }
 
 .channelName-3KPsGw {
   color: var(--primary-text-color);
 }
 
 .containerDefault-YUSmu3 .unread-36eUEm {
   background: var(--primary-text-color);
 }
 
 .containerDefault-YUSmu3 .modeSelected-3DmyhH .content-1gYQeQ,
 .containerDefault-YUSmu3 .modeSelected-3DmyhH:hover .content-1gYQeQ {
   background: #730000;
 }
 
 .containerDefault-YUSmu3 .modeSelected-3DmyhH .content-1gYQeQ .icon-2W8DHg {
   color: var(--primary-text-color);
 }
 
 .content-1gYQeQ .children-1MGS9G .iconItem-1EjiK0 svg {
   color: var(--primary-text-color);
 }
 
 .containerDefault-YUSmu3 .voiceUser-3nRK-K .content-1Tgc42 .username-vAneIW {
   color: var(--primary-text-color);
   font-weight: bold;
 }
 
 .containerDefault-YUSmu3
   .voiceUser-3nRK-K
   .content-1Tgc42
   .usernameSpeaking-3FKv6H {
   color: #ff0000;
 }
 
 .containerDefault-YUSmu3
   .voiceUser-3nRK-K
   .content-1Tgc42
   .avatarSpeaking-2pCGrZ {
   box-shadow: inset 0 0 0 1px #ff0000;
 }
 
 .containerDefault-YUSmu3 .list-2x9Cl9 .icons-2mwuFp .liveSmall-1Urjcy {
   background: #ff0000;
 }
 
 /* 
 ----------------
 SERVERS LIST BAR
 ----------------
 */
 
 .guilds-2JjMmN .scroller-3X7KbA,
 .bg-1QIAus {
   background: black;
 }
 
 .tutorialContainer-2jwoiB .circleIconButton-1VxDrg svg,
 .listItemWrapper-3d87LP .circleIconButton-1VxDrg svg {
   color: #ff0000;
 }
 
 .tutorialContainer-2jwoiB .selected-2r1Hvo,
 .listItemWrapper-3d87LP .selected-2r1Hvo {
   background: #ffffff;
 }
 
 .wrapper-28eC3z .lowerBadge-3WTshO .numberBadge-37OJ3S {
   background: var(--primary-text-color);
   color: black;
 }
 
 .listItem-3SmSlK .pill-22lZHo .item-2LIpTv {
   background: #ffffff;
 }
 
 .folder-241Joy .closedFolderIconWrapper-3tRb2d {
   background: #730000;
 }
 
 .folder-241Joy .expandedFolderIconWrapper-3RwQpD {
   background: #730000;
 }
 
 .folder-241Joy .expandedFolderIconWrapper-3RwQpD svg {
   color: #ffffff;
 }
 
 #bd-pub-button:hover {
   background: #ff0000;
 }
 
 /*
 ----------------------------
 MAIN CONTAINER WITH MESSAGES
 ----------------------------
 */
 
 .channelTextArea-1FufC0 .scrollableContainer-15eg7h {
   border-radius: 10px;
   background: #180000;
 }
 
 .channelTextArea-1FufC0 .buttons-uaqb-5 .buttonWrapper-3YFQGJ {
   color: var(--primary-text-color);
 }
 
 .chatContent-3KubbW .container-2sjPya .reaction-3vwAF2 {
   background: #320000;
   border-radius: 7px;
 }
 
 .contentWrapper-3vHNP2,
 .contentWrapper-3vHNP2 .header-11eigE {
   background-color: #180000;
 }
 
 .contentWrapper-3vHNP2 .navList-YSb9UB button {
   color: var(--primary-text-color);
 }
 
 .contentWrapper-3vHNP2 .navList-YSb9UB button[aria-selected="true"] {
   background: transparent;
   color: var(--primary-text-color);
   text-shadow: 0px 0px 25px var(--primary-text-color);
 }
 
 .contentWrapper-3vHNP2 .wrapper-1NNaWG,
 .wrapper-3u51GQ .emojiPicker-6YCk8a .header-1ULbqO {
   background: #000000;
 }
 
 .contentWrapper-3vHNP2 .wrapper-1NNaWG .header-1XpmZs,
 .emojiPicker-6YCk8a .header-1XpmZs {
   color: var(--primary-text-color);
 }
 
 .contentWrapper-3vHNP2 .header-11eigE .inner-1NoIT5,
 .contentWrapper-3vHNP2 .container-1SX9VC .inner-1NoIT5,
 .contentWrapper-3vHNP2 .header-2TLOnc .inner-2pOSmK,
 .wrapper-3u51GQ .emojiPicker-6YCk8a .inner-1NoIT5 {
   background: var(-primary-text-color);
 }
 
 .contentWrapper-3vHNP2 .categorySection-3j71bm {
   background: #000000;
 }
 
 .contentWrapper-3vHNP2 .categoryList-2qRrlj,
 .contentWrapper-3vHNP2 .inspector-DFKXwB,
 .contentWrapper-3vHNP2 .list-obNEuP,
 .wrapper-22rqw6 .list-obNEuP,
 .wrapper-22rqw6 .unicodeShortcut-3N8oDe,
 .emojiPicker-6YCk8a .inspector-DFKXwB {
   background: #000000;
 }
 
 .message-2CShn3 .repliedMessage-3Z6XBG::before {
   border-color: #ffffff;
 }
 
 .container-A2jo65 .replyBar-1oi75v {
   background: #320000;
   border-left: #180000 solid 1px;
   border-top: #180000 solid 1px;
   border-right: #180000 solid 1px;
 }
 
 .container-A2jo65 .replyBar-1oi75v .replyLabel-WWnhHi {
   color: #ffffff;
 }
 
 .messagesWrapper-RpOMA3 .newMessagesBar-1hF-9G {
   background: #320000;
 }
 
 .messagesWrapper-RpOMA3 .jumpToPresentBar-1cEnH0 {
   background: #320000;
 }
 
 .container-3XgAHv .container-1RZJZM .chat-1rZYgu {
   background: #180000;
 }
 
 .container-3XgAHv .container-1RZJZM .container-ZMc96U {
   background: black;
 }
 
 .chatContent-3KubbW .content-2a4AW9 .container-1yy5xN h1 {
   color: var(--primary-text-color);
 }
 
 .markup-eYLPri code {
   background: #180000;
 }
 
 .container-2sjPya .embedWrapper-1MtIDg .grid-1aWVsE {
   background: #000000;
 }
 
 .container-2sjPya .messageAttachment-CZp8Iv .attachment-1PZZB2 {
   border-color: #730000;
 }
 
 .container-2sjPya
   .messageAttachment-CZp8Iv
   .attachment-1PZZB2
   .filenameLinkWrapper-3Rc6sk
   a {
   color: var(--primary-text-color);
 }
 
 .container-2sjPya .messageAttachment-CZp8Iv .attachment-1PZZB2 {
   background: black;
 }
 
 .timestamp-p1Df1m time {
   color: var(--primary-text-color);
 }
 
 .divider-IqmEqJ {
   background: #730000;
 }
 
 .divider-IqmEqJ .unreadPillCap-2-iI4h {
   display: none;
 }
 
 .divider-IqmEqJ span {
   color: var(--primary-text-color);
   background: #180000;
 }
 
 .textContainer-36wgKK code,
 .footer-GXWBBp {
   background: #180000;
 }
 
 .avatar-2e8lTP {
   border-radius: 5px;
 }
 
 .wrapper-2vIMkT svg {
   color: var(--primary-text-color);
 }
 
 .messagesWrapper-RpOMA3 {
   margin-bottom: 1rem;
 }
 
 /*
 -------------------
 LEFT BOTTOM PROFILE
 -------------------
 */
 
 .panels-3wFtMD {
   background: black;
   padding-top: 0.25rem;
 }
 
 .panels-3wFtMD .title-338goq {
   color: #ffffff;
 }
 
 .panels-3wFtMD .contents-3ca1mk {
   color: var(--primary-text-color);
 }
 
 .container-YkUktl
   .avatarWrapper-1B9FTW
   .avatar-1EWyVD
   .avatarStack-3vfSFa
   .avatarSpeaking-33RRJU {
   box-shadow: inset 0 0 0 2px #ff0000;
 }
 
 .container-YkUktl,
 .container-1zzFcN {
   background: black;
 }
 
 /*
 --------------------
 DISCORD STARTUP VIEW
 --------------------
 */
 
 .container-2cd8Mz .container-ZMc96U {
   background: black;
   box-sizing: content-box;
 }
 
 .container-2cd8Mz
   .peopleColumn-1wMU14
   .peopleListItem-u6dGxF
   .actions-YHvpIT
   svg {
   color: var(--primary-text-color);
 }
 
 .container-2cd8Mz .peopleColumn-1wMU14 .inner-2pOSmK {
   background: #000000;
 }
 
 .container-2cd8Mz .peopleColumn-1wMU14 .title-x4dI75 {
   color: var(--primary-text-color);
 }
 
 .container-1oAagU h3 {
   color: #ffffff;
 }
 
 .container-1oAagU .itemCard-3Etziu {
   border-color: #000000;
 }
 
 .container-1oAagU .itemCard-3Etziu .activitySection-20iylG div {
   color: #ffffff;
 }
 
 .body-16rSsp .section-3G9aLW {
   background: #000000;
 }
 
 .container-1oAagU .emptyCard-KDifrB {
   background: #000000;
 }
 
 .base-2jDfDU .sidebar-1tnWFu .searchBar-3TnChZ {
   background: black;
 }
 
 .base-2jDfDU .sidebar-1tnWFu .searchBar-3TnChZ button {
   background: #180000;
 }
 
 .base-2jDfDU .scroller-WSmht3 .channel-1Shao0 {
   background: black;
   margin-bottom: 0.25rem;
 }
 
 .privateChannelsHeaderContainer-1UWASm .headerText-1qIDDT {
   color: var(--primary-text-color);
 }
 
 .chatContent-3KubbW .typingDots-1Y8dki .text-3S7XCz {
   color: #ffffff;
 }
 
 /* 
 -------------------
 CREATE SERVER POPUP
 -------------------
 */
 
 .theme-light .container-1Lk8p7,
 .theme-light .container-1Lk8p7 .flex-2S1XBF {
   background: #000000;
 }
 
 .theme-light .container-1Lk8p7 h3 {
   color: var(--primary-text-color);
 }
 
 .theme-light .container-1Lk8p7 div[data-text-variant="text-md/normal"] {
   color: var(--primary-text-color);
 }
 
 .theme-light .container-1Lk8p7 button[class="container-x8Y1ix"] {
   background: #ffffff;
   transition: all 0.2s;
 }
 
 .theme-light .container-1Lk8p7 button[class="container-x8Y1ix"]:hover {
   background: #ff0000;
 }
 
 .theme-light .container-1Lk8p7 .footerButton-24QPis {
   background: #ff0000;
 }
 
 .theme-light .container-1Lk8p7 .flex-2S1XBF button:hover {
   background: #ff0000;
 }
 
 /*
 ---------------------
 DISCORD SETTINGS PAGE
 ---------------------
 */
 
 .standardSidebarView-E9Pc3j {
   --background-tertiary: #000000;
   --background-modifier-selected: #730000;
   --input-background: #000000;
   --deprecated-card-bg: #000000;
   --header-secondary: var(--primary-text-color);
 }
 
 .standardSidebarView-E9Pc3j .authedApp-8q3NA9 {
   background: #000000;
 }
 
 .theme-dark .paymentPane-ut5qKZ,
 .theme-dark .bottomDivider-ZmTm-j,
 .theme-dark .paginator-1eqD2g,
 .theme-dark .codeRedemptionRedirect-2hYMSQ,
 .theme-dark .expandedInfo-1W31i3 {
   background: #000000;
 }
 
 /*
 -----------------------
 BETTER DISCORD SETTINGS
 -----------------------
 */
 
 .bd-button {
   background: #730000;
 }
 
 .bd-button:hover {
   background: #ff0000;
 }
 
 .bd-button-danger {
   background: #ff0000;
 }
 
 .bd-button-danger:hover {
   background: #ff0000;
 }
 
 .bd-view-button.selected {
   background: #ff0000;
 }
 
 .bd-empty-image-container {
   margin-top: 1rem;
   background: #000000;
 }
 
 .bd-addon-header {
   color: #ff0000;
 }
 
 /*
 --------------
 FORUM CHANNELS
 --------------
 */
 
 .theme-dark .container-3wLKDe {
   background: #000000;
 }
 
 .theme-dark .container-3wLKDe .form-25Aujy .titleContainer-2YK93J svg,
 .theme-dark .container-3wLKDe .form-25Aujy .inputMaxLength-3n06SD textarea {
   color: var(--primary-text-color);
 }
 
 .theme-dark
   .container-3wLKDe
   .form-25Aujy
   .inputMaxLength-3n06SD
   textarea::placeholder {
   color: var(--primary-text-color);
 }
 
 .theme-dark .container-3wLKDe .matchingPostsRow-2IiEQ1 h3 {
   color: var(--primary-text-color);
 }
 
 .startPostHelp-RNMDiS .text-xs-normal-3SiVjE {
   color: var(--primary-text-color);
 }
 
 .tag-19iIl1,
 .pill-3pRQlO {
   --background-tertiary: #730000;
   --background-secondary-alt: #ff0000;
 }
 
 .pill-3pRQlO.selected-24z1Ou {
   border-color: #000000;
 } 

```


