# tec-Vectrex
A Vectrex display for TEC-1

The Vectrex is a vector display-based home video game console–the only one ever designed and released for the home market, developed by Smith Engineering 1982.
The Vectrex was praised for its software library, unique graphical capabilities, and built-in monitor. It was the first console to have a 3D-based peripheral. The computer controls the vector generator, which makes the screen drawings. The computer controls the integration rates using a digital-to-analog converter, and the monitor uses voltage ramps to steer the electron beam. The Vectrex's cathode ray tube is a standard Samsung model 240RB40 manufactured for small black/white television sets. It uses a computer-controlled integrator and linear amplifier to direct the internal electron beam in a vector pattern. The light pen allows the user to create images and to indicate on the screen. It uses a photo-detector to track the pen's location and to change its pattern size as the pen moves.


### cct
- https://easyeda.com/editor#id=06fde9941fd74225a6f9060f40bda28a


### project
get the tec1 to drive two DAC into the xy of a cro or crt tube coil deflector. also modulate the beam on and off.
with code draw the vector graphics, use asm and MINT.

- drive cro xy inputs for visualization
- drive DAC 
- off 7 seg leds, run off 2 free ports
- off 8x8 led matrix, piggy back off exiting led muxing


### Iterate
- make oscilloscope music and drive the vectrex display, need two audio channels 
  - https://oscilloscopemusic.com/
  - https://oscilloscopemusic.com/software.php
  - https://oscilloscopemusic.com/oscistudio.php
  - https://www.blender.org/ or simialr
  - https://puredata.info/

- drive analog
  - xy yoke coils 2 monitor/tv/crt  
  - xy voice coil 2 laser pointer
  - dc motor
  - rf

- Cube https://github.com/SteveJustin1963/tec-8x8x8
- POV, circular spin, 16 leds with serial shift registers https://github.com/SteveJustin1963/tec-POV
- Touch keys-single, linear, matrix, circular 


### ref
- https://en.wikipedia.org/wiki/Scanimate
- https://www.redsharknews.com/scanimate-the-granddaddy-of-realtime-motion-graphics
- video synthesizer
- 
- https://www.google.com/search?q=ATtiny+Oscilloscope+on+VGA+monitor&rlz=1C1ASRM_enAU820AU820&sxsrf=ALeKk02Q-ARRys3SAoOIeTGdo-18TtZKnQ:1588774389193&tbm=isch&source=iu&ictx=1&fir=qWWHB7_GRwzXqM%253A%252C8Z56BaPpSiFjUM%252C_&vet=1&usg=AI4_-kSDis9gp1JmTJ5JfI9W06PB7CZuOQ&sa=X&ved=2ahUKEwi_8-HotZ_pAhV34zgGHX1RBX0Q9QEwAnoECAoQDg#imgrc=qWWHB7_GRwzXqM:
