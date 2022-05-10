# EnigmaMachine
A digital Enigma Machine using Python tkinter for the UI coded in the Jupyter Notebook.  
  
You can either run a string of text through the enigma machine without the UI or use the UI for real time key press response encoding like the original enigma machine used to use.  
  
The Machine used up to 10 pairs of unique letters for the plugboard.  
  
It has 5 different rotors that can be placed in any of three ordered positions. The rotor wirings were taken from https://en.wikipedia.org/wiki/Enigma_rotor_details from the table with rotors I-V of the Enigma 1 and M3 Army model name and number.  
  
Each rotor can be started in one of 26 positions.  
  
And finally there are 4 options for a reflector with wirings also taken from https://en.wikipedia.org/wiki/Enigma_rotor_details. Options: 'A', 'B', 'C', and 'Swiss'.  
  
With all these options there totals out at (26^3)*(5*4*3)*150,000,000,000,000 = 158.184 quintillion different initial conditions!  
