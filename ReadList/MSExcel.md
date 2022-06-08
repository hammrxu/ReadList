1. 💚 ctrl+D: FORMATTING: Copy the top one cell formula/data.
2. 💚 ctrl+R: FORMATTING: Copy the left one cell formula/data.
3. 💚 ctrl+H: REPLACE
4. 💚 ctrl+E: FORMATTING: fill selected cells with besides format/data. //may not work well if too complicated.
5. 💚 alt+=: AUTOSUM: select area(data and blank for sum inputs), press alt+=, autosumed! 💥 or press alt+= first, hit enter. 💥
6. 💚 ctrl+G: GOTO. complicated autosum? select area(data and blank for sum inputs), press ctrl+G, select 'blanks' that will go to blanks selected, and then do alt+=. autosumed! 💥 
7. 💚 =sumif(range,criteria,sum_range).  
  | Person| Apples Consumed | When|
  |---|---|---|
  |Alice(A2)|4(B2)| MON|
  |Bob(A3)|5(B3)|MON|
  |Alice(A4)|2(B4)| TUE|
  |Alice(A5)|3(B5)| WED|
  want to know how many apples Alice consumed a day? =sumif(A2:A5, A2, B2:B5)  
  want to know how many apples if Alice consumed a day more than 3? =sumif(A2:A5, A2>3, B2:B5)
