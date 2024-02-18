## Requirements

- git
- zsh installed and set up:
  1. Install zsh (e.g. `sudo nala install zsh`)
  2. Use zsh as default shell: `chsh -s $(which zsh)`
    * _Restart the user session to apply the change._
    * _`chsh` doesn't work in every system._

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
