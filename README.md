> This role is not meant to be shared. It is only used by myself.
> I use this role in my playbooks by adding the repo as a Git submodule.

# Ansible Role `krew`

Role that installs Krew, the package manager for kubectl plugins with Asdf.

- <https://github.com/kubernetes-sigs/krew>
- List of plugins: <https://krew.sigs.k8s.io/plugins/>

## Features

- Installs Krew and configures it for Bash and Zsh.
- Installs plugins with Krew I use.

## FAQ

### Set version of Krew?

Not possible. This role always installs / upgrades to the latest version of
Krew whenever it's run.
