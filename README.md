# Excel
This is to mainly understand the clear difference between VLOOKUP and XLOOKUP
Some of the differences that I can point out are:
Vlookup can look for values right or down of the lookup array only, whereas xlookup can look for values on any side 
Vlookup can return only one value(that is the return array can be only one column, whereas for Xlookup we can return more than 1 value(more than one return array can be selected)
Vlookup can return only the exact(false), or approximate item(True)
But whereas xlookup can return exact and approximate(this approximate can be based on mode- 0, 1, -1) to determine the next approximate value(either next lowest or next highest) and a wildcard character – 2, which is 
Vlookup only gives the first instance of the looked-up value, but in Xlookup we can define either the first or the next by defining the search mode as 1,0,-1
