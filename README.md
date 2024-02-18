A fork of [mcornella](https://github.com/mcornella)'s great dotfiles I adopted for personal use.

## Requirements

- git
- zsh installed and set up:
  1. Install zsh (e.g. `sudo nala install zsh`)
  2. Use zsh as default shell (e.g. `chsh -s $(which zsh)`)

## Usage

1. Download or clone repository:

   ```sh
   git clone git@github.com:bswck/dotfiles --recurse-submodules
   ```

   I personally use `gh`:
   ```sh
   gh repo clone bswck/dotflies -- --recurse-submodules
   ```

2. Run init script: `./init.zsh`

3. Restart the shell or run `exec zsh`
