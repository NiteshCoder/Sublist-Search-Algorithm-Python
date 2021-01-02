# Sublist-Search-Algorithm-Python
Tested code for Sublist Search Algorithm in Python.


Mainy Worls with Link List.

Real time Application :
	- Spell Checker
	- Search engine etc.
	
How it works ?
	-  Compare data and search(Pattern).
	-  If pattern and data both same then go ahead.
	-  Otherwise data still continue from current index
	-  But patter index set to base again.
	
	Undertand with Example :
		
		data   : AABBBBBBBBB
		patter : AB
		
		Step 1: Compare Data[0] and pattern[0] Same. So increment.
		
		Step 2: Compare Data[1] and pattern[1] Not same. 
				// Now Pattern Set to index 0 again.
				
		Step 3: Data[1] and pattern[0] Same.
		Step 4: Data[2] and pattern[1] Same.
		Step 5: FOUND EXIT.
					
