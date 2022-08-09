# mau-kmonad
My configurations for kmonad

## Todo
- Remove directory `user` from project structore (leave only mauedu).
- Update `bashrc-kmonad` to reflect change above.
- Move test files to specific folder.

## Using
1. Clone this repository to `~/Code`
2. Copy `bashrc-kmonad` to ~/.bashrc.d
3. `souce ~/.bashrc` to load `bashrc-kmonad`
4. Run the command `keyboard` in your shell.

## Building Kmonad executable from source
The bash script `docker-build.sh` will:
1. Install docker (including adding current user to `docker` group).
2. Clone kmonad repository.
3. Build kmonad executable using docker.
4. Move the executable to this repository under `~/Code/mau-kmonad/mauedu/`
