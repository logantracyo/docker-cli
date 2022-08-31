# docker-zsh-completion

[Zsh](http://zsh.org)-shell completion for [Docker](http://docker.io).

## How to Install

### Oh My Zsh

For [Oh My Zsh](http://ohmyz.sh/) users, execute these two lines:
```sh
mkdir -p ~/.oh-my-zsh/plugins/docker/
curl -fLo ~/.oh-my-zsh/plugins/docker/_docker https://raw.githubusercontent.com/docker/cli/master/contrib/completion/zsh/_docker
```
Then add `docker` to the plugins list in the `~/.zshrc` file, and run `exec zsh` to restart zsh and activate the new plugin.

### Other shells
This abbreviated document is based upon [its counterpart at the now-deprecated original repo](https://github.com/felixr/docker-zsh-completion/blob/master/README.md), which has installation instructions for other shells.
Those instructions reference the original repo, so at a minimum, the repo URL will need to be updated to be usable.
