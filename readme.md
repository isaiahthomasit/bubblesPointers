```text

void printValues(int *array){
  the function recieves an integer array as the functions parameters
  start the integer counter at 0
  repeat for loop while the counter is lex than MAX
  increase counter by 1 after each interation
  print the array element at the current counter position
  print newline at the end
}

swap(value1, value2){
  two pointers to int variable will be passed into the funtions parameters
  create a int temp variable for temporary values
  store value1 into temp
  copy value2 into value1
  copy temp into value2
}

sort(array){
  an array will be passed into the functions parameters
  start with the first pair of 2 elements within the array
  compare the two elements with if statement
  if element at position j > position j + 1, swap them
  increase j by 1 to move to next pair
  continue until j has reached the end
  increase i by 1 and repeat until array is sorted
}

int main(){
  create an int array named values
  print those value as "Before:" followed by a newline
  print the unsorted array
  create variables x and y for the swap test
  print the values of x and y
  pass the addresses of x and y into the swap() function
  print the values of x and y to verify swap

  pass the values array into the sort() function
  print "After:" followed by a newline
  pass the sorted values array into printValues
  return 0  
 
```
