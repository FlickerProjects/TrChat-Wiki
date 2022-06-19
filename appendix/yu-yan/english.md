---
description: English language support.
---

# 🇺🇸 English

> ### en\_US.yml

{% tabs %}
{% tab title="PasteBin" %}
[https://pastebin.com/mEvBqsRp](https://pastebin.com/mEvBqsRp)
{% endtab %}

{% tab title="Download" %}
[https://pastebin.com/dl/mEvBqsRp](https://pastebin.com/dl/mEvBqsRp)
{% endtab %}

{% tab title="Raw" %}
[https://pastebin.com/raw/mEvBqsRp](https://pastebin.com/raw/mEvBqsRp)
{% endtab %}

{% tab title="Print" %}
[https://pastebin.com/print/mEvBqsRp](https://pastebin.com/print/mEvBqsRp)
{% endtab %}
{% endtabs %}

```yaml
Plugin-Loading:
  - '&r'
  - '&7Loading &3Tr&bChat&7... &8{0}'
  - '&r'
Plugin-Enabled: '&8[&3Tr&bChat&8] &bINFO &8| &3Loaded. TrChat &av{0} &3has been enabled.'
Plugin-Loaded-Functions: '&8[&3Tr&bChat&8] &bCHAT &8| &3Loaded &b{0} &3chat functions... &8[{1} Ms]'
Plugin-Loaded-Channels: '&8[&3Tr&bChat&8] &bCHAT &8| &3Loaded &b{0} &3chat channels... &8[{1} Ms]'
Plugin-Loaded-Filter-Local: '&8[&3Tr&bChat&8] &aFILTER &8| &3Loaded local filter words &b{0} &3.'
Plugin-Loaded-Filter-Cloud: '&8[&3Tr&bChat&8] &aFILTER &8| &3Loaded cloud filter words &a{0} &3. &8[{1} - {2}]'
Plugin-Reloaded: '&8[&3Tr&bChat&8] &7Settings changed, reloaded...'
Plugin-Failed-Load-Filter-Cloud: '&8[&3Tr&bChat&8] &8Unable to update filter thesaurus from the cloud...'
Plugin-Proxy-Supported: '&8[&3Tr&bChat&8] &6Hooked &e{0} &6chat support.'
Plugin-Proxy-None: '&8[&3Tr&bChat&8] &7No proxy support currently'
Plugin-Dependency-Hooked: '&8[&3Tr&bChat&8] &6HOOK &8| &7Soft-Dependency &f{0} &7is hooked.'
Plugin-Updater-Latest: '&8[&3Tr&bChat&8] &2You''re running the latest version of &3TrChat&a.'
Plugin-Updater-Dev: '&8[&3Tr&bChat&8] &6You''re running the development version of &3TrChat&6'
Plugin-Updater-Header:
  - ''
  - '&3--------------------------------------------------'
  - '&7▪ &3TrChat &aUpdate Notify &8{0} &7➦ &8{1}'
Plugin-Updater-Footer:
  - '&7▪ &2Github: &a&nhttps://github.com/FlickerProjects/TrChat/releases'
  - '&3--------------------------------------------------'
Plugin-Debug-On:
  - type: title
    title: '&7&lDEBUG MODE'
    subtitle: '&3&lis now &a&lEnabled&3&l.'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 2
Plugin-Debug-Off:
  - type: title
    title: '&7&lDEBUG MODE'
    subtitle: '&3&lis now &c&lDisabled&3&l.'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 0
Plugin-Done: '&8[&3Tr&bChat&8] &fOperate successfully.'
Plugin-Failed: '&8[&3Tr&bChat&8] &cOperation failure.'

Error-Version: '&8[&3Tr&bChat&8] &cERROR &8| &7Plugin version error. Please re-download the plugin.'

General-Too-Long: '&8[&3Tr&bChat&8] &7Message is too long. &8[&6{0}&8/&2{1}&8]'
General-Too-Similar: '&8[&3Tr&bChat&8] &7Please do not repeat your message.'
General-No-Permission: '&8[&3Tr&bChat&8] &7You do not have enough permission to do this.'
General-Muted: '&8[&3Tr&bChat&8] &cYou have been muted until {0}!'
General-Global-Muting: '&8[&3Tr&bChat&8] &cAll members are being muted.'

Cooldowns-Chat:
  - type: actionbar
    text: '&7&lYou need to wait after &6{0} secs &7&lbefore chatting again.'
  - type: sound
    sound: 'ENTITY_ITEM_BREAK'
    volume: 1
    pitch: 2
Cooldowns-Item-Show:
  - type: actionbar
    text: '&3&lYou need to wait after &a{0} secs &3&lbefore showing your item again.'
  - type: sound
    sound: 'ENTITY_ITEM_BREAK'
    volume: 1
    pitch: 0
Cooldowns-Inventory-Show:
  - type: actionbar
    text: '&3&lYou need to wait after &a{0} secs &3&lbefore showing your inventory again.'
  - type: sound
    sound: 'ENTITY_ITEM_BREAK'
    volume: 1
    pitch: 0

Command-Controller-Deny: '&c&lYou can not use this command.'
Command-Controller-Cooldown: '&c&lYou need to wait after &6{0} secs &7&lbefore using this command again.'
Command-Not-Player: '&8[&3Tr&bChat&8] &cYou must be a player to do this.'
Command-Player-Not-Exist: '&8[&3Tr&bChat&8] &7The target player is not online or does not exist.'

Mentions-Notify:
  - type: actionbar
    text: '&d&l&k|&r &3&lPlayer &a&l{0} &3&lmentioned you in the chat &d&l&k|'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 2

Private-Message-Spy-Format: '&8[&3Spy&8] &6{0} &2-> &3{1}&f: &7{2}'
Private-Message-Spy-On:
  - type: actionbar
    text: '&c&l&k|&r &a&lSpy Mode Enabled &c&l&k|'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 2
Private-Message-Spy-Off:
  - type: actionbar
    text: '&c&l&k|&r &c&lSpy Mode Disabled &c&l&k|'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 0
Private-Message-No-Player:
  - type: actionbar
    text: '&3&lPlayer name required'
  - type: sound
    sound: 'ENTITY_ITEM_BREAK'
    volume: 1
    pitch: 0
Private-Message-No-Message:
  - type: actionbar
    text: '&7&lChat context required'
  - type: sound
    sound: 'ENTITY_ITEM_BREAK'
    volume: 1
    pitch: 0
Private-Message-Receive:
  - type: actionbar
    text: '&8[ &a! &8] &3You''ve received a message from &a{0} &3.'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 2

Channel-Proxy-Not-Enable: '&8[&3Tr&bChat&8] &7Unable to connect &eBungeeCord &7or &eVelocity &7.'
Channel-Join:
  - type: actionbar
    text: '&a&lJoined the {0} chat channel.'
  - type: text
    text: '&8[&3Tr&bChat&8] &3You''ve been into the {0} chat channel'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 2
Channel-Quit:
  - type: actionbar
    text: '&3&lLeft the {0} chat channel.'
  - type: text
    text: '&8[&3Tr&bChat&8] &7You''ve left the {0} chat channel...'
  - type: sound
    sound: 'BLOCK_ANVIL_LAND'
    volume: 1
    pitch: 0
Channel-No-Speak-Permission:
  - type: actionbar
    text: '&c&lYou have no speak permission of this channel'
  - type: sound
    sound: 'ENTITY_ITEM_BREAK'
    volume: 1
    pitch: 0

Mute-Muted-Player: '&8[&3Tr&bChat&8] &7You muted {0} for {1} minute(s).'
Mute-Muted-All: '&8[&3Tr&bChat&8] &7Global muted.'
Mute-Cancel-Muted-All: '&8[&3Tr&bChat&8] &7Global mute canceled.'
```
