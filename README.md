Create link to this folder so that Gemini loads these slash commands
```shell
git clone git@github.com:Linkeway/gemini-slash-commands.git ~/gemini_slash_commands
ln -s ~/gemini_slash_commands/commands  ~/.gemini/
```
## Commands
### gitlab-review
Review a MR on Gitlab and post the comments to Gitlab.

Prerequisite:
```shell
brew install glab
glab # this will ask for Gitlab access token
```
### review
Review branch locally.
