# Kill Switch

Automatically stops the bot when it reaches a certain performance threshold, which can be either positive or negative. This feature uses the same performance calculation methodology as the `history` command.

You will be prompted to configure kill switch  during the first setup.

The example below activates kill switch and tells it to stop the bot at a 5% loss:

```
Would you like to enable the kill switch? (y/n) >>>
y

At what profit/loss rate would you like the bot to stop? (e.g. -0.05 equals 5% loss) >>>
-0.05
```

You can always reconfigure this feature in two ways:

1. Editing `conf_global.yml` file using a text editor

2. Inside Hummingbot enter: `config kill_switch_enabled` and/or `config kill_switch_rate`
