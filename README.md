# devcontainer-dotfiles

Dotfiles are files and folders on Unix-like systems starting with . that control the configuration of applications and shells on your system. Your dotfiles repository might include your shell aliases and preferences, any tools you want to install, or any other codespace personalization you want to make.

You can configure GitHub Codespaces to use dotfiles from any repository you own by selecting that repository in your personal GitHub Codespaces settings.

When you create a new codespace, GitHub clones your selected dotfiles repository to the codespace environment, and looks for one of the following files to set up the environment.

```
install.sh
install
bootstrap.sh
bootstrap
script/bootstrap
setup.sh
setup
script/setup
```

If none of these files are found, then any files or folders in your selected dotfiles repository starting with . are symlinked to the codespace's ~ or $HOME directory.

Any changes to your selected dotfiles repository will apply only to each new codespace, and do not affect any existing codespace.

## Documentation

* [Dotfiles for Codespaces](https://docs.github.com/en/codespaces/customizing-your-codespace/personalizing-github-codespaces-for-your-account#dotfiles)
* [Enabling Codespaces to use Dotfiles](https://docs.github.com/en/codespaces/customizing-your-codespace/personalizing-github-codespaces-for-your-account#enabling-your-dotfiles-repository-for-codespaces)
* [ Configure codespace dotfile repository ](https://github.com/settings/codespaces) 