# tec-Vectrex
Vectrex display for TEC-1, well the start of one
https://easyeda.com/editor#id=06fde9941fd74225a6f9060f40bda28a


## goals
* expand visual display, 
  * add 2 extra 7 seg leds, run off 2 free ports
  * add integrated 8x8 led matrix, piggy back off exiting led muxing
* add stereo sound
* simple dac 
  * resistor array, piggyback off 7 seg leds
  * dac chip $4
  * drive cro xy inputs for visualization
  * ref- oscilloscope music, https://oscilloscopemusic.com/
  * asm/forth code, create similar effects
  * drive analog
    * xy yoke coils 2 monitor/tv/crt  
    * xy voice coil 2 laser pointer
    * dc motor
    * rf
* simple adc 
  * resistor array
  * analog in, audio, etc
  * adc chip $8
* 8x8x8 cube
* POV, circular spin, 16 leds with serial shift registers
* Touch keys-single, linear, matrix, circular
