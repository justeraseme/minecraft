# Chat Reports
Chat reports are a new addition added to Minecraft since 1.19.1, 
intended in mind for users and servers of all kinds. Chat Reports 
are optional for dedicated server owners (SMP runners, anarchy 
servers, etc) and **always on** for Realms.

## What are chat reports?

Chat reports is a message reporting system added by Mojang upon 
one of the pre-release snapshots of 1.19.1. In the version prior 
(1.19.0), Mojang added message signatures to messages, which had 
to be signed in order to chat.

In 1.19.1, this system was further expanded, requiring users to sign 
messages that could be reported.

## Why is this bad?
<!-- TODO: rework this? -->
Upon the release of 1.19.1, an exploit called Gaslight came out. 
The exploit manipulated how messages can be reported and resulted 
in complications, such as false bans for answering questions that 
were manipulated on report.

For example, if you said yes to "Do you like fruit?", the user of 
the exploit could make it sound like you answered a more sinister 
question, like "do you like to break the law?", which could then
in turn result in action taken against your account, and the user
losing access to an account they could use just fine prior.

The exploit seems to not be present on 1.20+, but by the time it came 
out, the exploit was already publicized and the damage was done. Since 
then, some players have taken a very solid stance on their feelings 
about this feature, and various mods made to make Reporting impossible 
have been created, including No Chat Reports and [FreedomChat](https://modrinth.com/plugin/freedomchat).

## What should I do?
If you don't really care, nothing will probably change; assuming you 
do not swear, do not call people names, you play on 1.20 and higher & 
not actively breaking Mojang's Community Standards, you should be okay. 
Keep in mind that some users are very strong about this topic, especially 
since it's a feature that locks some out of playing a game online that 
they paid for.

If you do care and might be worrying, what you do here will depend. If 
you play with friends over a dedicated server (i.e: Aternos, a paid 
dedicated server, self-hosted server), you can install [FreedomChat](https://modrinth.com/plugin/freedomchat) (Bukkit and forks) 
or [No Chat Reports](https://modrinth.com/mod/no-chat-reports) (Forge, Fabric, Quilt & NeoForge).

If you do not have have access to the server being hosted, all you 
can do is install [No Chat Reports](https://modrinth.com/mod/no-chat-reports) 
and hope for the best. If you are still worried and want to stay extra safe, 
either you'll have to avoid servers that enforce Chat Reports or you will have 
to kind whoever manages the server to install either mod on the server.

If you play on a server with reports on, you should **never** add a server's 
IP address to NCR's "whitelisted servers" section, under any circumstances, 
no exceptions. This allows servers to sign messages, and on server versions 
that are older (i.e: 1.19.1), you open yourself up at risk to being falsely 
reported. **This is a very unlikely possibility**, but still something you
should NEVER do, unless if you are sure the server is safe and prevents
chat reports.

**If you are on 1.19.0 and below**, you are unaffected. If you're on 
1.19.1 - 1.19.4 and are willing to be a little malicious, [Guardian](https://github.com/nodusclient/guardian) 
can prevent you from being reported, although it is against the server's 
will and may not be allowed by some servers.  
Additionally, some may not recommend you use Guardian, due to its 
sheer forceful implementation.

## How can I tell if Chat Reports are on?
There are a couple of ways. **You should follow these instructions**
**every time you join a server**, or else you may risk potential
complications involving the chat system.

Entries marked **(NCR)** involve stuff you can only check if 
you have the **No Chats Reports** mod installed. Remember to 
install **Mod Menu**, so you can configure mods in-game, 
**or you will not have a mods button**!

### 1. Bottom left indicator (NCR)
If you use the NCR mod and didn't turn off the mod's effects in
the multiplayer menu, you can see a little button on the bottom right
of your screen when chatting. For **Fabulously Optimized** users, it
will look like a shield, but for regular mod users, it will very likely
just be a simple colored icon, perhaps a circle with a question mark.

Just send an innocent message (like "Hi everyone!") in chat and see what
happens! If you did not get a popup warning with two buttons when you sent
a chat message, open the chat again and check the bottom right!

From there, hover over the icon and read what appears.

If you got a popup warning, read the next two sections **carefully**.


### 2. System Message indicator
If you are not using a modded version of the game (i.e: Lunar Client, 
Vanilla), and/or you do not have No Chat Reports installed, you usually 
see these indicators by default.

If not, go to the main menu (or pause menu) and click **Mods**. It may be an icon. 
Search for, or scroll down on the mods list on the left until you find 
**No Chat Reports**  and open it. Click the icon to open the settings (or click 
the mod name and click the gear on the right).

Click the **Client** tab and and set **Hide system message indicators** to **No**. You can
also set the other indicators (Modified, unverified) to No, if you wish.  
Then just hit **Save & Quit**.

From now on, you will see an indicator bar to the left of chat messages if messages are
game messages, or unsigned. If it is  **grey**, and the text "Game message" 
appears, then the server actively  prevents chat reports on the server end. 
If it is (likely) **yellow** and hovering over it says "Unverified", the message
is unsigned and/or unable to be verified with signing.  

If it says "Modified", then the message may have been modified by the server 
and/or might not be the message you're expecting. If there is no indicator at all,
the server may be signing messages. **Continue onto #3**.

### 3. Popup warning when sending messages (NCR)
This assumes you are using completely default settings, which most users
will most definitely be.

If you got a popup warning when sending a message in chat, this is
usually **your last warning** before you send messages that are signed
by the client. **Sometimes it is not a sign of danger**, some servers
(most notably FishOnMC) display the grey indicator of hope, even if
the warning popup says you may be in danger.

From here, you should only click "Allow Signing" if you
are confident that you are safe and in an enviornment you feel you
are safe and can't be falsely reported in (i.e: a space with no
malicious actors, a safe place with reports OFF.)

If your messages have no indicator (**AND** you did the last
section properly, including double checking), **the server may be**
**signing messages**.

Continue to the next section **before** you assume that the server
has reportable messages.

### 4. Checking "Social Interactions"
> [!CAUTION]
> This may not actually mean your messages are unreportable.  
> Have caution as you would any other server with reports available.

If you are on a server that disables chat reports, this step **is**
**unnecessary**. You may need to bind the "Social Interactions" key
if this button is not bound. You have to be in a server to see
that button. **The default keybind is P**.


On some servers, servers may appear to sign messages, but will have
the option to report chat messages **OFF**. You can check this by
clicking the warning triangle icon on any non-self player in the
social interactions menu! If the "Chat messages" button is not
clickable, then chat messages cannot be reported, even if they
are signed.

### 5. Checking the "chat messages" reporting menu itself!
> [!CAUTION]
> This may not actually mean your messages are unreportable.  
> Have caution as you would any other server with reports available.

Sometimes if you try to report chat messages of other people, they
never show any chat messages in the reporting menu at all, **with no**
**exceptions**. To check this, just go to Social Interactions, click
a player's warning icon, click "Chat messages" and see if any messages
come up!


## Further Reading
<!-- TODO: find more neutral resources -->

- [Chat Reporting Helper](https://modrinth.com/resourcepack/chat-reporting-helper) (A resource pack for 1.19.4+ that replaces No Chat Reports icons and some in-game text with more clearer information on how Chat Reporting works. Good if you are unsure what the harms are, or why this all matters to people.)
- [If you are a server owner, read No Chat Report's guide on how to secure your players.](https://github.com/Aizistral-Studios/No-Chat-Reports/wiki/Protecting-Server-Players)
- [If you're curious why we have to panic, review this exploit submitted by Nodus Client.](https://github.com/nodusclient/gaslight)
- [You could also install Guardian, a mod that makes you unreportable against the server's will. This may get you banned from servers. Linked is a fork that supports 1.20+.](https://github.com/z7087/guardian)