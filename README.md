## lgcommander.py
lgcommander.py is a python script for controlling your Smart Lg TV with your PC.
It can be used for gaining access to hidden menus and modes.

## To use it you need:
A PC, with python 3.x installed, connected to the same network as your Lg TV.

## Some useful codes:

* for EZ_ADJUST menu enter 255
* for IN START menu enter 251
* for Installation menu enter 207
* for POWER_ONLY mode enter 254

Warning: do not enter 254 if you do not know what POWER_ONLY mode is. You can find additional information about menus and modes here: <http://openlgtv.org.ru>   
 
As long as you do not "factory reset" your TV, pairing key doesn't change. You can use an editor to modify the line:

    lgtv["pairingKey"] = "DDGWAF"    

to suit your TV's actual pairing key.  This will eliminate the pairing key acquisition stage.


## Windows users:
You can avoid the black console window if you change the "py" file extension to "pyw".

#### This sowtware was developed with inspiration and/or information taken from:

*   <http://python.org>


*   <http://openlgtv.org.ru>


*   An application written in ruby where you can find a comprehensive list of command codes:    
<https://github.com/dreamcat4/lgremote>
