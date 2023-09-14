# my .gitconfig aliases

one-liner getting started:

```bash
# backup current local .gitconfig
mv -fv $HOME/.gitconfig $HOME/.gitcinfig-$(date +%Y-%m-%d)-backup
# install new .gitconfig
curl -sS https://raw.githubusercontent.com/daggerok/gitconfig/main/.gitconfig >> $HOME/.gitconfig
# and then type, for instance:
git cfg
```
