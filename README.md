/**
 * @name ALED PROJECT THEME
 * @description Stable v2.0
 * @author ALED PROJECT
 * @version 14.7
 * @authorId 470573716711931905
 * @invite rQHRex2
 * @website 
 */

@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/SettingsModal/SettingsModal.css);

:root {
	--settingsmodalbackground: transparent;
	--settingsmodalwidth: 960px;
	--settingsmodalheight: 80vh;
}

:root {
  --user-buttons-spacing: 8px;
  --avatar-left: 327.5px;
  --avatar-bottom: 26.5px;
  --avatar-radius: 5px;
  --status-radius: 3px;
  --status-menu-radius: 2px;
  --server-radius: 8px;
  --role-radius: 3px; 
  --role-circle: 12px;
  --avatar-width: 130px;
  --colored-emoji: grayscale(0%);
  --mention-color: #f04747;
  --unread-color: #7289da;
  --mention-color-bar: #C66262;
  --mention-color-background: #c662621f;
  --mention-color-hover: #c6626226;
  --spotify-in-discord__spotify-brand-color: #1ed760;
  --spotify-color: #1ed760 !important;
  --user-buttons-color: #fffd82;
  --chat-buttons: #6E85D3;
  --online: #43B581;
  --iddle: #FAA61A;
  --dnd: #F04747;
  --offline: #747F8D;
  --streaming: #593695;
  --tooltips: block;
  --discord-logo: none;
}
:root .panels-j1Uci_ > .container-3baos1 > .flex-1xMQg5 > .button-14-BFJ {
  color: var(--user-buttons-color);
}
:root .userPopout-xaxa6l .body-3HBlXn .bodyInnerWrapper-26fQXj .role-2irmRk {
  border-radius: var(--role-radius) !important;;
}
:root .userPopout-xaxa6l .body-3HBlXn .bodyInnerWrapper-26fQXj .role-2irmRk .roleCircle-3xAZ1j {
  width: var(--role-circle) !important;
  height: var(--role-circle) !important;
  border-radius: var(--role-radius) !important;
}
:root .userPopout-xaxa6l .avatarHint-2A3RNb {
  display: none;
}
:root .connectionIcon-2ElzVe {
  border-radius: 5px;
  padding: 4px;
}
:root .pointerEvents-2zdfdO {
  mask: none;
  pointer-events: none;
}
:root .pointerEvents-2zdfdO[width="8"]:not([mask="url(#svg-mask-status-online-mobile)"]), :root .pointerEvents-2zdfdO[width="10"]:not([mask="url(#svg-mask-status-online-mobile)"]), :root .pointerEvents-2zdfdO[width="12"]:not([mask="url(#svg-mask-status-online-mobile)"]), :root .pointerEvents-2zdfdO[width="16"]:not([mask="url(#svg-mask-status-online-mobile)"]) {
  rx: var(--status-radius);
}
:root .pointerEvents-2zdfdO[width="25"], :root .pointerEvents-2zdfdO[mask="url(#svg-mask-status-online-mobile)"] {
  rx: 5px;
}
:root .mask-1l8v16, :root .userInfo-2zN2z8 {
  overflow: visible;
}
:root .cursorDefault-dsQJ1n, :root .mask-1l8v16 > svg {
  overflow: visible;
}
:root .userPopout-xaxa6l .mask-1l8v16 > svg > mask > rect:first-child {
  x: 18;
  y: 14 !important;
  ry: var(--status-radius);
}
:root div:not(.avatarWrapper-2yR4wp) .mask-1l8v16 > svg > mask > rect:first-child {
  y: 8;
  rx: var(--status-radius);
}
:root .mask-1l8v16 > svg > mask > rect[width="10"]:first-child {
  x: 8;
  width: 14px;
  height: 11px;
}
:root .avatarWrapper-2yR4wp .wrapper-3t9DeA > .mask-1l8v16 > svg > rect {
  height: 25px;
  mask: none;
  x: 10;
  y: 8;
  width: 10px;
  height: 10px;
  rx: var(--status-radius);
}
:root .mask-1l8v16 > svg > rect {
  height: 40px;
}
:root .mask-1l8v16 > svg > mask > rect:nth-child(2), :root .mask-1l8v16 > svg > mask > circle, :root .mask-1l8v16 > svg > mask > polygon {
  display: none;
}
:root .channel-2QD9_O .pointerEvents-2zdfdO,
:root .members-1998pB .pointerEvents-2zdfdO,
:root .avatarWrapper-2yR4wp[aria-expanded=false] .pointerEvents-2zdfdO,
:root .peopleListItem-2nzedh .pointerEvents-2zdfdO,
:root .nowPlayingColumn-2sl4cE .pointerEvents-2zdfdO {
  height: 12px;
  y: 24;
  stroke-width: 2.5px;
}
:root .channel-2QD9_O .pointerEvents-2zdfdO[width="10"]:not([mask="url(#svg-mask-status-online-mobile)"]),
:root .members-1998pB .pointerEvents-2zdfdO[width="10"]:not([mask="url(#svg-mask-status-online-mobile)"]),
:root .avatarWrapper-2yR4wp[aria-expanded=false] .pointerEvents-2zdfdO,
:root .peopleListItem-2nzedh .pointerEvents-2zdfdO[width="10"]:not([mask="url(#svg-mask-status-online-mobile)"]),
:root .nowPlayingColumn-2sl4cE .pointerEvents-2zdfdO[width="10"]:not([mask="url(#svg-mask-status-online-mobile)"]) {
  width: 12px;
  x: 24;
}
:root .channel-2QD9_O .pointerEvents-2zdfdO[mask="url(#svg-mask-status-online-mobile)"],
:root .members-1998pB .pointerEvents-2zdfdO[mask="url(#svg-mask-status-online-mobile)"],
:root .peopleListItem-2nzedh .pointerEvents-2zdfdO[mask="url(#svg-mask-status-online-mobile)"],
:root .nowPlayingColumn-2sl4cE .pointerEvents-2zdfdO[mask="url(#svg-mask-status-online-mobile)"],
:root .menu-3sdvDG .pointerEvents-2zdfdO[mask="url(#svg-mask-status-online-mobile)"] {
  width: 12px;
  height: 16px;
  x: 24;
  y: 20;
}
:root .avatarWrapper-2yR4wp[aria-expanded=true] .pointerEvents-2zdfdO {
  x: 24;
  y: 24;
}
:root .listAvatar-1NlAhb .pointerEvents-2zdfdO {
  x: 30;
  y: 30;
  stroke-width: 2.5px;
}
:root .menu-3sdvDG .pointerEvents-2zdfdO:not([mask="url(#svg-mask-status-online-mobile)"]) {
  width: 10px;
  height: 10px;
  stroke-width: 2.5px;
}
:root .menu-3sdvDG .pointerEvents-2zdfdO {
  stroke: var(--background-tertiary);
}
:root .channel-2QD9_O .pointerEvents-2zdfdO, :root .members-1998pB .pointerEvents-2zdfdO, :root .listAvatar-1NlAhb .pointerEvents-2zdfdO, :root .nowPlayingColumn-2sl4cE .pointerEvents-2zdfdO {
  stroke: var(--background-secondary-alt);
}
:root .avatarWrapper-2yR4wp[aria-expanded=false] .pointerEvents-2zdfdO, :root .peopleListItem-2nzedh .pointerEvents-2zdfdO {
  stroke: var(--background-primary);
}
:root .wrapper-3t9DeA .dots-3Bkt3k {
  overflow: visible;
}
:root .wrapper-3t9DeA .dots-3Bkt3k g {
  transform: translateY(2.5px);
}
:root .userPopout-xaxa6l .pointerEvents-2zdfdO {
  x: 66;
  y: 66;
  width: 20px;
  height: 20px;
  rx: calc(var(--status-radius) + 1px) !important;
  stroke-width: 4px;
  stroke: var(--background-tertiary);
}
:root .userPopout-xaxa6l .pointerEvents-2zdfdO[mask="url(#svg-mask-status-online-mobile)"] {
  x: 64;
  y: 56;
  height: 28px;
  rx: 8px !important;
}
:root .wrapper-3t9DeA foreignObject, :root .callAvatarMask-1SLlRi foreignObject,
:root .avatarContainer-3CQrif foreignObject, :root .avatarMasked-3y6o4j {
  mask: none;
  -webkit-mask: none;
}
:root .wrapper-3t9DeA, :root .avatar-1BDn8e, :root .profile-1eT9hT .avatarUploaderInner-3UNxY3,
:root .voiceAvatar-14IynY, :root .avatar-3tNQiO, :root .border-Jn5IOt, :root .avatar-3bWpYy, :root .clickableAvatar-1wQpeh,
:root .emptyUser-7txhlW, :root .avatar-VxgULZ, :root .wrapper-2QE8vf.ringingIncoming-38YcLn::after,
:root .wrapper-2QE8vf.ringingOutgoing-mbXhhQ::after, :root .replyAvatar-1K9Wmr, :root .avatarSpeaking-2c8-9i,
:root .avatar-3Heyg_, :root .avatarContainer-2LLZwy, :root .appAvatar-3bgkQ9 {
  border-radius: var(--avatar-radius);
}
:root .wrapper-25eVIn foreignObject {
  mask: none;
  -webkit-mask: none;
}
:root .wrapperSimple-19ogV2 {
  overflow: visible;
}
:root .wrapperSimple-19ogV2, :root .wrapper-25eVIn foreignObject,
:root .folderIconWrapper-226oVY, :root .folderIconWrapper-1_bOZe,
:root .expandedFolderBackground-2sPsd-,
:root .flexChild-faoVW3 .avatarUploaderInner-3UNxY3 {
  border-radius: var(--server-radius);
}

/** ---- Chat Area ---- **/
.noChannel-Z1DQK7 .image-1GzsFd {
  width: 480px !important;
  height: 293px !important;
  background-image: url("https://images2.imgbox.com/44/ba/e7Bdvoxc_o.jpg") !important;
}
.emojiButton-3uL3Aw {
  margin-right: 14px;
}

/** ---- Member Area ---- **/
.members-1998pB {
  margin-top: -10px;
}
.member-3W1lQa {
  margin: 0;
  border-radius: 0;
}
/** ---- Status menu ---- **/
.status-1AY8sU {
  border-radius: var(--status-menu-radius);
}
foreignObject[mask] {
  mask: unset;
}

/** ---- Scrollbars ---- **/
::-webkit-scrollbar {
  display: none;
}
.messages-3amgkR.scroller-2FKFPG::-webkit-scrollbar {
  display: initial;
}
#app-mount .scroller-2FKFPG::-webkit-scrollbar-track-piece {
  background: transparent;
}
#app-mount .scroller-2FKFPG::-webkit-scrollbar-thumb {
  min-height: 2px;
}

/** ---- BetterDiscord Stuff ---- **/
