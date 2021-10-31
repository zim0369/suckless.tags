# suckless.tags

__Script to go to a tag and move master window to a tag with ease.__

*There has been an update.

I've placed the script under /usr/local/bin

```
const char *tagcmd[]      = {"st", "-f", "Fira Code:size=13", "-n", "tag", "-g", "36x6",  "-e", "tags", NULL };
```

I created a scratchpad that calls the script.

It'd be better to map the command to toggle the scratchpad to a dedicated key instead of combination to reduce number of keypresses.

### The script first asks you for the action.

- Press g to go to a workspace and m to move the master window to a workspace.

- If you chose g then now choose an alphabet or a number to go to that workspace.

- If you chose g then now choose an alphabet or a number to move master to that workspace.

__NOTE:__

_The script uses xdotool so please change the key names in the script accordingly._

_You can use alphabets as well as numbers._
