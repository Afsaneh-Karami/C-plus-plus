# Sorting an array of random numbers from minimum to maximum:
In this code, I create a list of 12 random numbers by using the rand() function from the cstdlib library. To create distinguished numbers in every run of the program, I applied srand() function.<br />
I also used dynamic variable a for the array. <br />
There are two functions in the program swap and selection_sort.<br />
swap function is used two reference inputs and changes the value of them, for example, if x=2 and y=3 after applying the swap function they change to x=3 and y=2.<br />
selection_sort function is looking for the minimum value in the array. So, at first, put a[0] as the minimum value and then by a loop go through other numbers in the array and compare them with a[0] if they are lower, choose them as min value.<br />
During applying the selection_sort swap function change the position of array x and m.<br />
