A fork of [mcornella](https://github.com/mcornella)'s great dotfiles I adopted for personal use.

## Requirements
- git
- zsh installed and set up (`sudo nala install zsh && chsh -s $(which zsh)`)

## Usage

1. Clone this repository:

   ```sh
   git clone git@github.com:bswck/dotfiles --recurse-submodules
   ```

   I personally use `gh`:
   ```sh
   gh repo clone bswck/dotfiles -- --recurse-submodules
   ```

2. Run the initialization script: `dotfiles/init.zsh`

3. Restart the shell or run `exec zsh`
