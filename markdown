# Documentation

lcd.py 

  method: 
    showInScreen (textUp,textDown, isAvailable )
      initialize the lcd screen and receive 3 strings
  
  attributes:

internet.py 

import lcd.py 
  methods: 
    init()
    
    enterZone()
    
    exitZone()
  
  attributes:

parkingGeneric.py

import internet.py
  method:
  initParking(ZoneNumber) 
    read the enter button and the exit sensor
    receive an integer "The number of Zone"
  
  attributes:
  
parkingZone1.py

import parkingZone1.py
  attributes:
  ZoneNumber that is an int that save the number of zone  
  call initParking passing ZoneNumber as a parameter
