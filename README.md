# telegram_simulation_bot

Interact with your computing cluster via telegram to get realtime information on your running jobs.

<p align="middle">
  <img src="https://user-images.githubusercontent.com/7556347/120806225-e1b43b80-c546-11eb-8880-9ced55b58f32.PNG" width="250" />
  <img src="https://user-images.githubusercontent.com/7556347/120806232-e2e56880-c546-11eb-9f70-50900ab1b69e.jpeg" width="250" />
</p>

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
* `status <name>/all` - responds the status of `<name>` or all
* `error <name>/all` - responds errors of `<name>` or all
* `progress <name>/all` - responds the progress of `<name>` or all
* `convert <name>/all` - submits a slurm job called `exorad_convert` in `<name>` or all

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
