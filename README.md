# safe_rm-Fish-Script
Fish script to prevent accidental deletion. 
For Bash Script, use : [safe_rm-Bash](https://github.com/alphaxleonidas/safe_rm-Bash)


# Configuration:

```
echo $SHELL
```
If output: /bin/fish , proceed with: 

```
cd ~
git clone https://github.com/alphaxleonidas/safe_rm-Fish/
cp -rv safe_rm-Fish/config.fish ~/.config/fish/
rm -rv safe_rm-Fish
source ~/.config/fish/config.fish
```
This will activate the script.

To edit:

```
nano ~/.config/fish/config.fish
```
