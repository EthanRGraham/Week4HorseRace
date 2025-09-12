Make a constant int NUM_HORSES
make a constant int TRACK_LENGTH = 15;


main()
make an array of 5 0 values, call it horses
int horse[] = {0,0,0,0,0}; 
Set keepGoing to true
while keepGoing;
  run through each horse in the array
  advance that horse (if it received heads on the coin flip) use function advance for each horse. in there it will decide if that horse's value increases.
  print that horses name
  if that horse won, set keep going to false 
  ask user for input to start the next turn. 

advance () parameter is the horses itself. "lets advance horse number 2"
for each horse in the array
    flip a coin (using randomization) 0 or 1
    coin = whatever is rolled and then is added to that horse position in the array
    return the new value of the horse

  given a horse number and the array of horses
  roll a 0 or 1 value, place it in coin
  add coin to the horse's position value in the array


Printlane()
given a horse number and the array of horses
loop from zero to TRACK_LENGTH
if the current loop index is equal to the horse's value
print horse' id 
otherwise 
print a "."

the horses aren't moving, we are just re-printing the track

for horse in NUM_HORSES;
  print "." from 0 to TRACK_LENGTH
    if loop index is == value of horse;
        print horse's id 
              \n
  
  i(the horse of that row will be printed when the loop is = to the value of the horse.)
  
isWinner ()
if horse reaches end set keepGoing to false

make a print statement "OMG horse(i) = winner"

result = false
check each horses position, if it is greater than TRACKLENGTH
result = true
print Horse(id) won!
return result








