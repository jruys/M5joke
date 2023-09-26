# M5joke
Joke-O-matic using generic thermal printer on M5Stack Atom Lite

This uses a generic TTL level thermal printer on the Grove port.
When you press the button on the Atom it fetches a joke from 
official-joke-api.appspot.com, removes any Unicode, formats it
to 32 characters wide and prints.

The formatting routine is clunky, but I wanted to build it in
Blockly instead of Python.
