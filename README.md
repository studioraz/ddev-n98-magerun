# ddev-n98-magerun

A DDEV add-on to install the n98-magerun2 CLI in your project via `ddev add-on get`.

## Installation

```bash
cd your-project
ddev add-on get studioraz/ddev-n98-magerun
ddev restart
```

Once running, you can use:

```bash
ddev n98 list
```

If the command is not recognized, ensure the `commands/web/n98` script is executable:

```bash
chmod +x .ddev/commands/web/n98
```

## Uninstallation

```bash
ddev add-on remove ddev-n98-magerun
```

This will clean up both the wrapper and the downloaded PHAR.
# ddev-n98-magerun
