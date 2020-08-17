# Addition

Scenario: add two positive integers
  
  Given The calculator in on state

  When we enter a positive number within the range, press '+' sign, enter another positive number within the range and press '=' sign.
  
  Then we get the resultant sum of the two positive numbers entered (also within range).
  
  
Scenario: Add two positive numbers whose sum is out of range.
  
  Given the calculator is on, we enter a positive number, a '+' sign and another positive number 
  
  When we press '=' sign.
  
  Then it displays on the screen "Result is out of range. Please enter smaller numbers."

Scenario: (describe a scenario here)
  
  Given (state the initial condition)
  
  When (state the event)
  
  Then (state the effect)

Scenario: (describe a scenario here)
  
  Given (state the initial condition)

  When (state the event)
  
  Then (state the effect)

Scenario: (describe a scenario here)
  
  Given (state the initial condition)
  
  When (state the event)
  
  Then (state the effect)
