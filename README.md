# CECS-174-Lab-5
A program that compares the relative strength of two earthquakes, given their magnitudes using the moment magnitude scale

1. get_magnitude(number): function asks the user to input a earthquake magnitude. The number parameter is an integer that
identifies which earthquake (1 or 2) the user is being asked about, the number must be included in the output. Then the user 
will enter the magnitude which must be validated as positive (they do not need to be whole numbers), then return that number.

2. compare_magnitudes(magnitude1, magnitude2): function takes two magnitude values as parameters, and assumes that magnitude1 >
magnitude2. It calculates and returns the relative strength

3. get_run_again(): function asks the user if they want to compare two more earthquakes, it is called from main to determine if 
the main should loop again. The user must enter a 1 to continue, any other value means quit

4. main(): drives the program. It calls get_magnitude twice and stores the results in variables, then determines which variable 
is larger and calls compare_magnitudes, passing the larger magnitude as magnitude1. It then prints the results of the comparison,
then calls get_run_again. 

Research portion:

1. Find the magnitude of these earthquakes:
  a. 2011 Tohoku earthquake, Japan
  b. 1989 Loma Prieta earthquake, San Francisco, USA
  c. 2010 Haiti earthquake
  
2. What is the relative strength difference of the 2011 Tohoku earthquake vs. the 2010 Haiti earthquake?

3. How many people died in the Tohoku and Haiti earthquakes?
