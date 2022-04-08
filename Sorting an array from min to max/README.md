# Sorting an array of randonm number from minimum to maximum:
In this code, I creat a list of 12 randonm number by using rand() function from the cstdlib library. In order to creat a distiguished number in every run of the program I applied srand().
I also used dynamic variable a for array. 
There are two function in the program swap and selection_sort.
swap function is used two refrence input and change the value of them, for example if x=2 and y=3 after applying swap function they change to x=3 and y=2.
selection_sort function is looking for minimum value in the array. So, at first put a[0] as minumum value and then by a loop go throught other numbers in array and compare them with a[0] if they are lower choose as min value.
During applying selection_sort swap function change the position of array x and m.
