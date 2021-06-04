# telegram_simulation_bot

Interact with your computing cluster via telegram to get realtime information on your running jobs.

## Installation
From pypi:
```
pip install telegram_simulation_bot
```

## Usage

Change into the directory of your simulation and type:

```
telegram_simulation_bot
```

You will be prompted (only once) to configure `telegram_simulation_bot`.

## Commands
### MITgcm:
The following commands in telegram are possible:

* `list` - responds a list of currently running bots
* `status <name>` - responds the status of `<name>`
* `error <name>` - responds errors of `<name>`
* `progress <name>` - responds the progress of `<name>`

### Others:
There are currently no other simulation types implemented. Feel free to open up a PR for a new simulation type.

## Uninstallation
Remove configuration files using:
```
telegram_simulation_bot --delete
```
Remove the package using:
```
pip uninstall telegram_simulation_bot
```


