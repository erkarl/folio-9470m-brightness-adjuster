folio-9470m-brightness-adjuster
===============================

Brigthness adjuster for HP EliteBook Folio 9470m on Ubuntu 12.04 LTS

Add script to your $PATH 
---------------------
Make a new directory for scripts if you haven't already 
```console
mkdir ~/bin
```

Copy the script to your scripts directory 
```console
cp brightness ~/bin/brightness
```

Give the script proper permissions 
```console
chmod +rx ~/bin/brightness
```

Open .bashrc in some text editor 
```console
vim ~/.bashrc
```

Insert the following line to add scripts directory to your PATH
```console
export PATH=$PATH:$HOME/bin
```

Usage
---------------------
```console
'brightness {{brightness_value}}'
```

Examples
```console
'brightness 1500'
'brightness max'
```

{{brigthness_value}} == integer from 0 to 3484
