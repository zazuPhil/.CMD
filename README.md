# .CMD
Sten sax påse kod

import random 
import os
import re
os.system('cls' if os.name=='nt' else 'clear')
while (1 < 2):
    print "\n"
    print "Sten, Sax, Påse - Kör!"
    userChoice = raw_input("Välj ditt val [St]en], [S]ax, or [P]åse: ")
    if not re.match("[SsRrPp]", userChoice):
        print "Välj ett:"
        print "[St]en], [S]ax, or [P]åse."
        continue
    // Echo the user's choice
    print "Du väljer: " + userChoice
    choices = ['St', 'S', 'P']
