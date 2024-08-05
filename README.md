# Cyndex
A python cli tool for gathering binaries and popular apps your using and creating an ansible playbook

## TODO

### Set up

- [ ] editor
- [ ] linting
- [ ] other standards
  - what is PEP
- [ ] .env
- [ ] package management
 - Rye / Poetry
- [ ] database
  - sqlite
    - what is a good lib for python sqlite
- [ ] cross plat compat
  - support Macos and Linux, Linux first
- [ ] locations of installed binaries (brew / cargo etc.)
  - what bin paths should I support, though I will likely set it up in the DB so you can add it later
- [ ] templates for script creation
  - I need to read the docs for [Ansible Python 3 API](https://docs.ansible.com/ansible/latest/dev_guide/developing_api.html) and see how I can leverage it
- [ ] docker environment for testing the scripts (linux base, macos compat)
- [ ] diffing for only adding stuff thats not already tracked (efficiency)
- [ ] cli for wrapping up all the features

# Editor
- I will be using a mix of nvim and bpython
  - [ ] set up linting in neovim
  - [ ] set up lsp in neovim
  - [ ] set up debuggin in neovim
  - any other good stuff

## Package Management

- I have been reading about [RYE](https://github.com/astral-sh/rye) and would like to use it, otherwise second choice will be Poetry
- [Rye Documentation](https://rye.astral.sh/guide/)


