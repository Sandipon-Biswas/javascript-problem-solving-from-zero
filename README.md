# javascript-problem-solving-from-zero
Write a JavaScript Function   printNumber that takes an integer N and prints all the numbers between 0 to N.
Example:
Input: 5
Output: 0 1 2 3 4 5
Constraints:
0 < N 

```base
solve
function  printNumber(N){
    for(i=0;i<N+1;i++){
        console.log(i)
    }
}
printNumber(5)
```




Write a JavaScript function countWords  that takes a string and returns the number of words contained in this string. 
Example:
Input: ”Lorem ipsum dolor sit amet consectetur”
Output: 6

```base
function  countWords (str){
let words = str.split(" ");
let wordCount = words.length;
console.log(wordCount); 
}
countWords ("amar sonar blangla ami tomai vlobasi")
```





Constraints:
using built-in functions is prohibited

Write a JS function AreaOfTringle that takes the base and height of a triangle and returns its area.
Example 1:
Input: 7, 8
Output: 14
Explanation: Base 7 and height 8. After calculation,its area is 14.
Example 2:
Input: 10, 10
Output: 50  

Constraints:
Base cannot be negative 
Height cannot be negative
```base
function   AreaOfTringle (B,H){
{B>0 && H>0 && console.log(R=(B*H)/2);  }   
}
AreaOfTringle(60,60)
```
