# The-Go-Board-PS2-keyboard-reader
## Part 1 - Keyboard Operation Verification.

Before starting the project, the  correct operation of the PS/2 keyboard is verified. 
The keyboard is connected, through a PS/2 breakout board, to a logic level converter.   
A logic analyzer is connected to the 3.3V outputs of the logic level converter.

### The folowing keys are pressed sequentially on the keyboard
| key | expected scancode |
| - | - | 
|Press 1 | 16  |
|Release  1 | F016 |
|Press 2 | 1E |
|Release  2 | F01E |
|Press 3 | 26|
|Release  3 | F026 |
|Press A |  1C | 
|Release  A | F01C |
|Press B | 32 |
|Release  B | F032 |
|Press C | 21 | 
|Release  C | F021 |

### The following output is observerd with the logic analyzer.
The waveform for the press and release of the 1st key ( number 1 ) is shown.    
The list of all the recognised keypresses is shown in the table on the right side of the waveform.  


![1Press](1Press.png)

![1Release]( 1Release.png) 