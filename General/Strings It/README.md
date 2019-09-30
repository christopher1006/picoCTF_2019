# Strings It - General

## Points: 100

## Question 
  > Can you find the flag in file without running it? You can also find the file in /problems/strings-it_4_e276260a1b64a734b4178a280d25b754 on the shell server.
## Hint
  > strings (https://linux.die.net/man/1/strings)
## Solution
 The file is ELF. Run `strings strings` to grab all of the strings and send it to a separate file for `grep "picoCTF"` to analyze.
### Flag
`picoCTF{5tRIng5_1T_c611cac7}`
