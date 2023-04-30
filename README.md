# passage-store

This is a template for a password store. It is based on the [passage](https://github.com/FiloSottile/passage) password manager. It is intended to be used with [dotfiles](https://github.com/entelecheia/dotfiles).

## Usage

1. Create a private repository from this template.
2. Install [dotfiles](https://github.com/entelecheia/dotfiles).
3. When initializing dotfiles, select your private repository as the store for your passage passwords.

## Some notes

- If you need to initialize dotfiles manually, run `chezmoi init --apply`.
- If you need to initialize a new password store manually, run `passage-init`.
- If you need to generate a age key manually, run `dotfiles-setup-age`.

## [Helper commands](https://dotfiles.entelecheia.ai/usage/)

- `passage-init`: Initialize a new password store.
- `pass-push`: Push changes to the remote repository.
- `pass-pull`: Pull changes from the remote repository.
- `pass-sync`: Push and pull changes to and from the remote repository.
- `pass-insert`: Insert a new password.
- `pass-rm`: Remove a password.
- `pass-show`: Show a password.
- `pass-clone`: Restore a password store from a remote repository.
  
