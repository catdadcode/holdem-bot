Welcome to Hold'em Bot!

Check out the commands below to begin!  
If you'd like to find people to play with, check out the Hold'em Bot discord server: https://discord.gg/TGzd9T3

If you have any issues please submit them [here](https://github.com/chevtek/holdem-bot/issues).

---------------

**`$bankroll, $bank [user]`**  
_(DM or Channel)_  
Show a user's bankrolls.
> **`--user <@mention>`**  
> @mention a user to show their bankrolls. Defaults to yourself if no user is mentioned.

**`$create`**  
_(Channel Only)_  
Create a Hold'em table in the current channel.  
> **`--min-buy-in <number>`**  
> Specify a minimum buy-in amount for the table. Default is $1000.  
> **`--no-sound`**  
> Disable sound effects for this table.  
> **`--small-blind <number>`**  
> Specify the amount of the small blind. Default is $10.  
> **`--big-blind <number>`**  
> Specify the amount of the big blind. Default is $20.  
> **`--buy-in <number>`**  
> Specify the amount you, as the creator, intend to bring to the table. Default is the table minimum buy-in.  
> **`--turn-timer <number>`**  
> The number of seconds a player has to act on their turn. Default is 45 seconds. Specify 0 to disable turn timers.  
> **`--auto-destruct-timer <number>`**  
> The number of minutes before an idle table self-destructs.  
> **`--reset`**  
> Create a new table and override any existing table.  

**`$deal, $d`**  
_(DM or Channel)_  
Deal the cards and begin the hand! The table creator or the player in the dealer position can run this command.

**`$sit, $s [seat] [buy-in]`**  
_(Channel Only)_  
Take a seat at the active Hold'em table.  
> **`--seat <number>`**  
> Specify which seat you'd like to take at the table.  
> **`--buy-in <number>`**  
> Specify the amount of money to bring to the table. Defaults to the minimum buy-in for the table.

**`$stand [user]`**  
_(DM or Channel)_  
Stand up from your current table. If you are the table owner you can optionally specify a user to forcibly remove them.  
> **`--user <@mention>`**  
> @mention a user to remove that user from the table. Only allowed if you're the table owner.

**`$leaderboard, $lb`**  
_(Channel Only)_  
Display a list of all player bankrolls for this server.

**`$hands`**  
_(DM or Channel)_  
Show poker hand rankings guide.

**`$terms`**  
_(DM or Channel)_  
Display a glossary of poker terminology.

**`$refresh, $r`**  
_(DM or Channel)_  
Refresh the current table. Useful if the table has been scrolled out of view by chatter.

**`$destroy`**  
_(Channel Only)_  
Destroy the current table. This command can only be issued by the table creator.