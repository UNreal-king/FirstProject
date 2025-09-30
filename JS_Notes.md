# Javascript Notes

## Variable Declaration

let - is used to declare variables that can later be changed  
Example:
 ```let twin = 2;
 console.log(twin)
 2
 twin = 4
 console.log(twin)
 4```

 const - is used to declare variables that should not change  
 Example:
 ```
 const eat = 3;
 console.log(eat)
 3

 eat = 7;
 TypeError
 ```
+, -, %, //, **,*

//floor division
console.log(Math.floor(flu/print))

to make a comment = //

## Statements in Javascript If, If ..else, if ... else if ...else

let first = 10
let second = "10"
console.log(first == second)
true
console.log(first === second)
false

Exercise
Give an example use case of:
1. an "if" statement
2. an "if ... else " statement
3. an "if ... else if ... else" statement

# loop?
## for Loop

for (initialization; condition; increment){
    // code that ruvery time
}

for (let i = 4; i > 0; i--){
    console.log("Phil")
}

-- minus 1
++ plus 1

// Output
i = 4
Phil
i = 3
Phil
i = 2
Phil
i = 1
Phil
i = 0
