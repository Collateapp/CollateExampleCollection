---
title: Fenced Code Blocks
tags: []
type: markdown
modified: '2017-04-04T16:34:05.216Z'
---
**Javascript**
```javascript
for(i=1;i<101;i++)console.log((x=(i%3?'':'Fizz')+(i%5?'':'Buzz'))?x:i);
```

**Python**
```python
for i in xrange(1, 101):
    if i % 15 == 0:
        print "FizzBuzz"
    elif i % 3 == 0:
        print "Fizz"
    elif i % 5 == 0:
        print "Buzz"
    else:
        print i
```

**R**
```r
xx <- x <- 1:100
xx[x %% 3 == 0] <- "Fizz"
xx[x %% 5 == 0] <- "Buzz"
xx[x %% 15 == 0] <- "FizzBuzz"
xx
```

**MATLAB**
```matlab
function fizzBuzz() 
    for i = (1:100)
        if mod(i,15) == 0
           fprintf('FizzBuzz ')
        elseif mod(i,3) == 0
           fprintf('Fizz ')
        elseif mod(i,5) == 0
           fprintf('Buzz ')
        else
           fprintf('%i ',i)) 
        end
    end
    fprintf('\n');    
end
```

**Ruby**
```ruby
1.upto(100) do |n|
  print "Fizz" if a = (n % 3).zero?
  print "Buzz" if b = (n % 5).zero?
  print n unless (a || b)
  puts
end
```

**Brainfuck**
```brainfuck
FizzBuzz
 
Memory:
  Zero
  Zero
  Counter 1
  Counter 2
 
  Zero
  ASCIIDigit 3
  ASCIIDigit 2
  ASCIIDigit 1
 
  Zero
  Digit 3
  Digit 2    
  Digit 1    
 
  CopyPlace
  Mod 3
  Mod 5
  PrintNumber
 
  TmpFlag
 
Counters for the loop
++++++++++[>++++++++++[>+>+<<-]<-]
 
Number representation in ASCII
>>>>
++++++++ ++++++++ ++++++++ ++++++++ ++++++++ ++++++++ [>+>+>+<<<-]
<<<<
 
>>
[
    Do hundret times:
 
    Decrement counter
    ->->
 
    Increment Number
    > >>+> 
        > >>+>
        <<<<
    <<<<
 
    Check for Overflow
    ++++++++++
    >>> >>>>
    >++++++++++<
    [-<<< <<<<->>>> >>> >-<]
    ++++++++++ 
    <<< <<<<
 
    Restore the digit
    [->>>> >>>-<<< <<<<]
    >>>> [-]+ >>>>[<<<< - >>>>[-]]<<<< <<<< 
 
    If there is an overflow
    >>>>[
        <<<<
 
        >>>----------> >>>----------<+<< <<+<<
 
        Check for Overflow
        ++++++++++
        >> >>>>
        >>++++++++++<<
        [-<< <<<<->>>> >> >>-<<]
        ++++++++++ 
        << <<<<
 
        Restore the digit
        [->>>> >>-<< <<<<]
        >>>> [-]+ >>>>[<<<< - >>>>[-]]<<<< <<<< 
 
        If there (again) is an overflow
        >>>>[
            <<<<
            >>---------->> >>----------<+< <<<+<
 
            >>>>
            [-]
        ]<<<<
 
        >>>>
        [-]
    ]<<<<
 
    >>>> >>>> 
 
    Set if to print the number
    >>>[-]+<<<
 
    Handle the Mod 3 counter
    [-]+++
 
    >>>>[-]+<<<<
    >+[-<->]+++<
    [->->>>[-]<<<<]
    >>>>[
        <[-]>
 
        [-]
        Print "Fizz"
        ++++++++ ++++++++ ++++++++ ++++++++
        ++++++++ ++++++++ ++++++++ ++++++++
        ++++++.
 
        ++++++++ ++++++++ ++++++++ ++++++++
        +++.
 
        ++++++++ ++++++++ +..
 
        [-]
        <<<--->>>
    ]<<<<
 
    Handle the Mod 5 counter
    [-]+++++
 
    >>>>[-]+<<<<
    >>+[-<<->>]+++++<<
    [->>->>[-]<<<<]
    >>>>[
        <[-]>
 
        [-]
        Print "Buzz"
        ++++++++ ++++++++ ++++++++ ++++++++
        ++++++++ ++++++++ ++++++++ ++++++++
        ++.
 
        ++++++++ ++++++++ ++++++++ ++++++++
        ++++++++ ++++++++ +++.
 
        +++++..
 
        [-]
        <<----->>
    ]<<<<
 
    Check if to print the number (Leading zeros)
    >>>[
        <<< <<<< <<<<
        >.>.>.<<<
        >>> >>>> >>>>
        [-]
    ]<<<
 
    <<<< <<<<
 
    Print New Line
    <<<<[-]++++ ++++ ++++ +.---.[-]>>
]
<<
```




