# Ban Lister

Ban Lister gathers bans from trusted secure servers and compiles a free to use public repository.

This plugin is connected to BanLister's ever-growing repository, allowing you full control over your user's fate when they don't meet your standards.

### Installation

Download the ZIP file and extract ```BanLister-ServerGuard``` addon to the addons folder.

### Configuration

Open ```sv_banlister.lua``` from the ```lua/autorun/server``` directory and modify the following fields as follows.
```
BanLister.MaxBans = 15 -- If the user has equal to or more recorded bans then this value, then the user will be kicked from the server.
BanLister.RangeBans = "month" -- "total" - "month" -- MaxBans Time period.
BanLister.KickHim = false -- if false, instead of kicking users for MaxBans a message will be sent to staff. If true a message won't be sent and the user will be kicked.
BanLister.KickReason = "Sorry %s but this server is protected by Ban Lister ensuring a safe community" -- %s = player name
BanLister.AdminMessage = "%s has %d bans in the past month recorded" -- %s = player name
```

### Security

Our developers are committed to ensuring a full working and secure plugin. This plugin connects securely to our database to retrieving data when necessary. If you have further safety concerns or general questions you're more then welcome to come and chat to a developer https://discord.gg/F7FH2nn
