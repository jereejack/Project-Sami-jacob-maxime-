# Prague City University Chatbot

This chatbot is made by Sami, Jeremy and Maxim for "Prague Parks". It is made for tourists and Prague citizens to have useful info about parks in Prague. The chatbot can tell the user what different parks have and what can be done in them (ride bike, have a lunch etc.). This is the first part of the chatbot, that will be built upon in the next part of the project.


## Installation and how to use the chatbot
We have used clojure to write this chatbot and you need to install theses components :

- Leiningen
- A Command Line Interface (CLI)
 
1) After you write Lein run the chatbot will automatically start
2) On the first chatbot's question you should answer just with your name, because this name he will use later on
3) The Second question have to contain word Stromovka as it is the only park the chatbot knows
4) In the third question you can ask on these topics: opening hours, playground, refreshments, food, dogs, biking, skating, toilet and attractions
5) If you want to exit the chatbot just write 'end' or 'bye'

## Exemple of the output
```
> Hello. What is your name?

Maxim

> Which park do you want information about? I've information about parks in Prague

Stromovka

> What do you want to know about the park?

are dogs allowed

> For dogs : yes pets are allowed at the park
...
```
## Options

This chatbot knows only about park Stromovka and it's utilites


## Bugs 

If you report bugs , thanks to write and report at bughere@fixme.com


## License

Copyright © 2021 FIXME

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.
