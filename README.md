folio-9470m-brightness-adjuster
===============================

Brigthness adjuster for HP EliteBook Folio 9470m on Ubuntu 12.04 LTS

Add script to your $PATH 
---------------------
-make a new directory for scripts if you haven't already (mkdir ~/bin)
-copy the script to your scripts directory (cp brightness ~/bin/brightness)
-give the script proper permissions (chmod +rx ~/bin/brightness)
-open .bashrc in some text editor (vim ~/.bashrc)
-insert the following line (export PATH=$PATH:$HOME/bin)

Usage
---------------------
'python adjust_brightness.py {{brightness_value}}'

Example: 'python adjust_brigthness.py 1500'

{{brigthness_value}} == integer from 0 to 3484


