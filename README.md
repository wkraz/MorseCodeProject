# Morse Code Reader

This is a project I created in EE10200. 

In this project, I used the ELEGOO MEGA 2560 microcontroller to control my circuit. The goal of this project was to be able to read morse code inputs and translate them into words.
To do this, the input sensors I used were buttons and potentiometers, and the output sensors I used were an LCD and an LED. Button1 represented a "dot" in the Morse Code system, 
while Button2 represented a "dash". To signal the start of a new letter, the user turns the knob of the potentiometer all the way from the left to the right. Then a green LED lights 
up to signify that they can begin clicking the buttons. Then, they click the two buttons in whatever sequence they like, with a maximum of 4 entries. 
Then they turn the knob to the middle and the LED turns off. Then when they get the message that their letter has been entered, they have the choice to turn the knob to the left
and end the word, or turn the knob to the right and enter another letter. This process continues until the knob is turned to the left. 
Then, every letter the user entered is concatenated into a word and that word is displayed on the LCD. 
