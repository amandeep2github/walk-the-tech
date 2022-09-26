## Quotes
Make it work, make it right, make it fast  
refactoring reduce the cost of adding a feature in the future  
don't refactor while adding a feature and check in separately  

> smells  
naming  
long functions  
flow control not simple  
duplication - every line/logic which is repeated 
SLAP - single level of abstraction principal  
magic numbers  
low cohesion e.g. business logic in GUI  
tight coupling makes testing difficult  
comments telling what code is doing instead of why  
clever coding over clear coding  
constructor doing more than initialization if yes use constructor methods  
poor representation of domain e.g. in tictactoe using 2D array  
cyclomatic complexity is more than 1  
static not bad always  
from the domain problem to the bits and bytes there is no or very less abstraction  



> steps of refactoring  
write test case even if had to write in same class  
compose methods  
remove duplication  
introduce redundancy  
change code and test cases separately  
any code which is required only for testing keep it in test cases e.g. file writer  
seek feedback on refactoring early on  

