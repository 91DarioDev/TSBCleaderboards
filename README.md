# TSBCleaderboards
### An extension of [TopSupergroupsBot](https://github.com/91DarioDev/TopSupergroupsBot) to post leaderboards in channels

**The goal of this repo is to get groups data from** [TopSupergroupsBot](https://github.com/91DarioDev/TopSupergroupsBot)**, create leaderboards, and post the message on a telegram channel.**

#### How does it work?
The `config.py` file contains some parameter that needs to be adjusted.

The `example.py` file is an example on how to run one of the available leaderboards (in `leaderboards` folder).
The script can be run via cron on intervals.

The `already_joined` folder is a sort of .txt files database to keep trace of the channels that already joined the leaderboard, to mark them with the 'back' or 'new' emoji.

Along with the leaderboard sent in the desired channel, the admin will also receive in private chat a copy of new updated database as a backup.
