# Message Content — Engineer Karl demos

**Gold headers:** intent-provided events or content. **Silver headers:** setup, context, or results.

Separate demo pages:

- [1. Compromised-account response](message-content-compromised-accounts.md)
- [2A and 2B. In-game contests and moderation](message-content-in-game-chat.md)

## 1. Compromised-account response

### Trap channel

![Trap channel for bots and compromised accounts](assets/demos/compromised-accounts/01-trap-channel-stage.png)

### Spam posted by the compromised account

![Compromised account spreading phishing spam](assets/demos/compromised-accounts/02-compromised-account-stage.png)

### Trap-channel post before removal

![Account posts in the trap channel before removal](assets/demos/compromised-accounts/03-trap-channel-post-stage.png)

### Spam cleanup and evidence preservation

![Karl forwards image evidence to the private staff log during cleanup](assets/demos/compromised-accounts/04-cleanup-and-evidence-stage.png)

### Message and server invite

![Karl sends account-security instructions and a server invite](assets/demos/compromised-accounts/05-message-and-invite-stage.png)

## 2. In-game contests and moderation

### 2A. Contest points

Karl reads the `=D` marker and in-game username in forwarded chat, matches the username to a Discord account, and awards staff points.

**1. Announcement posted in-game**

![In-game announcement by Chance_25 containing the =D contest marker](assets/demos/chat-blasts/01-announcement-stage.png)

**2. Announcement forwarded to #in-game-chatter**

![The same announcement forwarded to Discord by the separate game-chat service](assets/demos/chat-blasts/02-forwarded-announcement-stage.png)

**3. Karl matches the member and awards points**

![In-game announcement matched to a Discord account and credited with staff points](assets/demos/chat-blasts/03-member-match-and-credit-stage.png)

### 2B. In-game chat moderation

Karl reads forwarded in-game messages and alerts staff to suspected abuse.

**1. Message posted in-game**

![In-game chat message reporting spam](assets/demos/chat-moderation/01-in-game-message-stage.png)

**2. Message forwarded to #in-game-chatter**

![The in-game message forwarded to Discord by the separate game-chat service](assets/demos/chat-moderation/02-forwarded-chat-stage.png)

**3. Karl alerts staff**

![Karl detects a keyword in the forwarded message and pings staff](assets/demos/chat-moderation/03-moderator-alert-stage.png)
