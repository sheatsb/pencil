# PencilSharp

For the new computers (of the old ones that need to be brought into line).

## Instructions 
- Git clone this repo and `cd pencil`
- Run `chmod +x bootstrap osprefs .grabs.local && chmod 755 *`
- Check the files in */stuffs* and */dotfiles* edit as needed
- Run `./bootstrap`, this is the main command, it'll run the main steps to install apps, etc
- Sit back and let the script run! If there's a problem, you can re-run the script.
- ***(optional)*** Run `./osprefs` for MacOS optimizations
- Set up services like Dropbox, connecting UTC to the font server, etc.


## Here's what it does: 

1. Makes ZSH the default shell 
2. Installs Homebrew and core packages
3. Installs node and npm (and select packages)
4. Installs rbenv and the latest Ruby (and select Gems)
5. Installs valetplus, a superset of Laravel Valet functions
6. Installs applications to */Applications* from Homebrew and an S3/DO Spaces bucket
7. Sets a whole lot of presets with the __osprefs file__
8. Cleans everything up to make it nice and tidy
