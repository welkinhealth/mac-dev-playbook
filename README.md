# instructions:
- first install homebrew (https://github.com/Homebrew/install)
- install ssh pub/priv key first, and ensure that ssh key is added to github account
- then use git to check out this repository
- then install ansible: `brew install ansible`
- then `ansible-galaxy install -r requirements.yml` in this repo root
- then `ansible-playbook -i inventory main.yml -K`

Misc:
- to get Spectacle preferences set you need to open it after its installed, look at preferences, quit Spectacle and re-run the playbook

