<div align="center">

<img src="icon/icon.png" width="110" alt="ASJTikTok">

# ASJTikTok

**Privacy, download and playback options for TikTok — without changing how the app looks.**

<sub>English and Arabic</sub>

Add the source in Sileo, Zebra, Cydia or Installer:

```
https://asjrx.github.io/
```

[**ASJ Tweaks on Telegram**](https://t.me/ASJTweaks) — new tweaks and update notes

</div>

---

## Where it lives

Everything is off after a fresh install — turn on only what you want. Two ways in: a button inside your profile menu, and a row inside TikTok's own Settings.

<p align="center">
  <img src="screenshots/entry.png" width="31%" alt="The button in the profile menu">
  <img src="screenshots/settings.png" width="31%" alt="The settings screen">
  <img src="screenshots/menu.png" width="31%" alt="The save menu on a video">
</p>

The button on the right of any video opens the save menu: **Save video**, **Save audio**, **Save profile picture**, **Copy username**, **Copy introduction**, **Clear display** and **Copy video information**. On a photo post it saves the whole slideshow instead.

---

## Features

### Feed
<img src="screenshots/feed.png" width="30%" align="right" alt="Feed settings">

- **Content country** — watch another region's For You
- **Remove ads**
- **Skip suggested accounts**
- **Hide LIVE**
- **Open on Following**
- **Hide safety warnings** and **sensitive content warnings**

<br clear="right">

### Playback
<img src="screenshots/playback.png" width="30%" align="right" alt="Playback settings">

- **Auto scroll** — move to the next video when one ends
- **Prevent video loop** — pause at the end instead of replaying
- **Play sound in muted videos**
- **Always show progress bar**
- On the video: **country**, **like count** and **upload date**

<br clear="right">

### Messages
<img src="screenshots/messages.png" width="30%" align="right" alt="Message settings">

The three privacy switches are built to work **one way only** — you keep seeing everyone, they stop seeing you.

**Hide message views** — you read a message and the sender is never told. No "Seen" appears on their side, and it stays that way even if you open the chat, scroll it and reply later.

**Always show read receipts** — the catch with TikTok's own privacy switch is that it is mutual: turn read receipts off and you stop seeing theirs too. This keeps their "Seen" visible to you while yours stays hidden. Use it together with the one above and the exchange becomes one-sided in your favour.

**Alert when read** — the moment someone opens your message you get told, which is the piece TikTok never shows you.

**Hide active status** — same idea for the green "active now" dot. TikTok's own Activity status setting hides you *and* blinds you at the same time. This one switches it off for reporting only: you keep seeing who is active, in the inbox and inside chats, while nothing about you is sent. It does not just flip the setting — every path that reports your presence is stopped, cold launch, account switch and the periodic timer included, and the report request itself is refused if anything still tries.

**Full last seen time** — "2h ago" becomes the exact time.

**Keep deleted messages** — when someone unsends a message it stays in the chat instead of turning into "This message was deleted". You read what they took back.

**Save DM GIFs** — GIFs get a save option; photos and videos already use TikTok's own.

<br clear="right">

### Profile
<img src="screenshots/profile.png" width="30%" align="right" alt="Profile settings">

**Anonymous viewing** — you can open any profile and no entry is added to their visitor list. The view is never reported, so there is nothing for them to see later either.

**Hide my story views** — watch a story and your name does not join the viewer list.

**Save stories** — every story you open is kept on your device as you saw it. Stories expire after a day and can be deleted by their owner; the copy you kept does not. They collect in their own screen inside the tweak, searchable by account.

**Show "Follows you"** — the badge TikTok shows on some profiles and not others, shown consistently.

**Sort any profile by most liked** — TikTok gives that sort for your own profile only. This gives it for anyone's.

**Longer bio** — write past the character limit.

**Show video count** and **Open links in Safari** — small ones: the number of posts on a profile, and profile links opening in Safari instead of the in-app browser.

<br clear="right">

### Comments, LIVE and downloads
<p>
  <img src="screenshots/comments.png" width="24%" alt="Comment settings">
  <img src="screenshots/live.png" width="24%" alt="LIVE settings">
  <img src="screenshots/downloads.png" width="24%" alt="Download settings">
  <img src="screenshots/stories.png" width="24%" alt="Saved stories">
</p>

- **View disabled comments**, **longer comments**, **save comment media**
- **Auto like button** for LIVE — draggable, with a count limit
- **Remove watermark** and **clean copied links**
- **Save profile picture**, **copy username**, **copy bio**
- Saved stories are collected in their own screen

### Extras

**Arabic and English** — the panel follows TikTok's own language, so an Arabic install gets Arabic screens without setting anything. A Language row lets you override it either way, and the layout mirrors with the text: the arrows turn, the rows read from the right, and the badge on a profile says يتابعك.

**Clear Display** — one tap hides the entire interface: buttons, captions, tab bars, everything. The video plays clean, and a small button brings it all back. Useful for actually looking at a video, or for a screenshot without the clutter.

**Content country** — the For You feed follows a region you pick instead of where you are.

**Remove watermark** — saved videos come without the TikTok watermark burned into the corner.

**Community tab** — TikTok sometimes opens with that tab missing from the top bar. It comes back within a moment instead of staying gone for the whole session.

---

## Install

### Jailbroken

Add the source above, or download a package from [Releases](../../releases) and install it with Sileo or Zebra.

| Jailbreak | Package |
|---|---|
| Dopamine / palera1n (rootless) | `ASJTikTok` — `iphoneos-arm64` |
| checkra1n / unc0ver and similar (rootful) | `ASJTikTok` — `iphoneos-arm64e` |
| roothide | `ASJTikTok (roothide)` |

Sileo picks the right architecture on its own; roothide is a separate entry.

### TrollStore

Fully supported, with a build of its own that keeps TikTok's own entitlements and all nine app extensions intact.

**[asjrx.github.io/trollstore](https://asjrx.github.io/trollstore)** — iOS 14.0–16.6.1, and 17.0 on some devices.

One link: on an iPhone with TrollStore it hands the file straight over, anywhere else it just downloads.

### Not jailbroken, no TrollStore

Download `ASJTikTok.dylib` from [Releases](../../releases) and inject it into your own copy of TikTok with Sideloadly or eSign, then sign and install.

> The dylib is self-contained and does not need Cydia Substrate, so any injector works.
> TikTok itself is not distributed here — bring your own copy.

---

## Notes

- Built against TikTok 46.4.0, arm64 and arm64e
- Screenshots are from a real install, not mockups

<div align="center"><sub>by <a href="https://github.com/asjrx">ASJRX</a></sub></div>
