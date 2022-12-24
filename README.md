# hackerank-array-question
 You will be given an array of  integers and you have to print the integers in the reverse order.

Input Format

The first line of the input contains ,where  is the number of integers.The next line contains  space-separated integers.

Constraints


, where  is the  integer in the array.

Output Format

Print the  integers of the array in the reverse order, space-separated on a single line.



Approach -  
 
 
 code:   
 #include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
      int n;//declare integer 
      cin>>n;// take input 
      int arr[n]; // declare array and put input from n 
      for(int i=0; i<n;i++){ 
          cin>>arr[i]; // take input in array
      }
      for(int i=n-1; i>=0;i--){
          cout<<arr[i]<<" ";
      }
    return 0;
}
