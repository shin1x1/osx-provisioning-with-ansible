# osx provisioning playbook
 
Inspired by https://github.com/mawatari/mac-provisioning
 
## Usage
 
```
$ git clone this_repo
$ cd this_repo
$ ansible-playbook -i hosts osx.yml
```
 
## Usage with dotfiles and ssh role（for me）

```
$ git clone this_repo
$ cd this_repo
$ vi osx.yml
  roles:
    - homebrew
    - homebrew-cask
    - ruby
    - dotfiles # uncomment this line
    - ssh # uncomment this line

$ ansible-playbook -i hosts osx.yml --ask-vault-pass
Vault password: # <--- Enter vault password
```

## Licence

MIT
