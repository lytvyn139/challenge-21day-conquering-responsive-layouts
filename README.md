# Conquering Responsive Layouts
21 day of challenge for responsive design deep dive

### Installing
you just need VS Code, ATOM, etc

## Running the tests
check console for errors

## Authors
Kevin Powell kevinpowell.co

## Day 1
by default web sites are responsive
use % not px ! 
the default undeclared width of child is - 100%=> 100% of parent element, parent also have have parent  -> a body is 100% view port.

## Day 2 
Challenge 

## Day 3
for best UE don't forget to use max-width:

## Day 4
If you need give something a height - DON'T !
use EM's & REM's
 5 em = 16px default font size * 5 (em) = 80px 

## Day 5
Challenge. If you put margins in px, lets say 100px each side, it's gonna look good on big screens,
but on iPHONE 6 you can't afford to give 200px of screen space for that. that why use:
.container {
  width: 80%;
  max-width: 750px;
  margin: 0 auto;
}
if you wan't the less white space on what's ever in that container, use width 50% it's gonna use 50% of (80% parent)

## Day 8
Flexbox Basics. 
Divs are 100% width by default
Flexbox item they trying to shrink to the smallest size that they can be
if no content they will not be displayed.
but if you want empty displayed but .col width 100%
gap: 100px is only supported in firefox, let's say you have 3 col and you want gaps between them
you can select two right colums by
.col + .col {
  it's starts from right and looks for siblings
}


## Day 9
Flexbox Challenge

## Day 11
Nav finished



