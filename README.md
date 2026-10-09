# macOS-coke
A zsh helper utility to turn on and off global caffeinate assertions to prevent sleep.

Obviously if you want to really get into it, nohup or screen caffeinate with other conditions, but I really just want to be able to keep my laptop awake at will.

If you’re using caffeinate on a server, you probably want to run caffeinate -s via /Library/LaunchDaemons.

You can integrate this into your .zshrc/.zsh_profile, or you can pull off the function wrapper and just make it a little shell script. If you do that, some of the little fiddly bits become redundant, like unfunction.
