bash-config
===========

Installation
------------
```
git clone https://github.com/JGShaw/bash-config .bash-config 

cat >>~/.bashrc <<EOS
  if [[ -f ~/.bash-config/bash_adam ]]; then
    source ~/.bash-config/bash_adam
  fi
EOS
```

Check for shellshock vulnurability
-----------------------------------

To check if you are vulnerable to the shellshock bug in bash run:

```
check_shellshock
```
