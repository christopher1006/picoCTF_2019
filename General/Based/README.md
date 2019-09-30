# Based - General 

## Points: 100

## Question 
  > To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with nc 2019shell1.picoctf.com 7380.
## Hint
  > I hear python can convert things.
  
  > It might help to have multiple windows open
## Solution
  Upon connecting, there are 45 seconds on the clock to convert a binary number that changes upon each login to ASCII.
  Next, convert a series of octal values to ASCII.
  Next, convert a series of hex values to ASCII.
  Retrieve the flag
### Flag
`picoCTF{learning_about_converting_values_819ada06}`
