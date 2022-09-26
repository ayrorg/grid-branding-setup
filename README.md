# Grid Branding – Computer Setup

To get started, you'll need to install Homebrew. You can do that by running this command:

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

To install the [common programs], run this:

```shell
curl https://raw.githubusercontent.com/ayrorg/grid-branding-setup/main/Brewfile | brew bundle --file=-
```

[common programs]: https://github.com/ayrorg/grid-branding-setup/blob/main/Brewfile

Next, you'd want to choose which category to install.

### Advisors

Read more here: https://github.com/ayrorg/grid-branding-setup/blob/main/advisors/Brewfile

```
curl https://raw.githubusercontent.com/ayrorg/grid-branding-setup/main/advisors/Brewfile | brew bundle --file=-
```

### Creatives

Read more here: https://github.com/ayrorg/grid-branding-setup/blob/main/creatives/Brewfile

```
curl https://raw.githubusercontent.com/ayrorg/grid-branding-setup/main/creatives/Brewfile | brew bundle --file=-
```

### Project Managers

Read more here: https://github.com/ayrorg/grid-branding-setup/blob/main/project-manager/Brewfile

```
curl https://raw.githubusercontent.com/ayrorg/grid-branding-setup/main/creatives/Brewfile | brew bundle --file=-
```
