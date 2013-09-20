folio-9470m-brightness-adjuster
===============================

Brigthness adjuster for HP EliteBook Folio 9470m on Ubuntu 12.04 LTS

Add script to your $PATH 
---------------------
mkdir ~/bin
cp brightness ~/bin/brightness
chmod +rx ~/bin/brightness
vim ~/.bashrc 
# Add personal scripts to path
export PATH=$PATH:$HOME/bin

Usage
---------------------
'python adjust_brightness.py {{brightness_value}}'

Example: 'python adjust_brigthness.py 1500'

{{brigthness_value}} == integer from 0 to 3484


