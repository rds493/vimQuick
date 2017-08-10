# vimQuick

----------------------

## normal mode: `Esc`
## insert mode: `i`

----------------------

## Move Left: `h`
## Move Right: `l`
## Move Up: `k`
## Move Down: `j`

----------------------

## Move to start of next word: `w`
## Move to end of word: `e`
## Move to beggining of word: `b`

----------------------

``` 
Combine previous commands with a number in the beggining 
to create more dynamic movement around the text
```

Example: `5w` moves the cursor 5 words forward
----------------------

## Insert repetitions of a word: <number>i<word> 

Example: 
```
30i- creates 30 "-" 
```
```
20iRick creates 20 "Ricks"
```

----------------------

## Find the occurence of a character: `f<char>`
## Find a specific occurrence of a characterL: `<number>f<char>`

Example: `5fq` finds the fifth occurrence of "q" in the text

----------------------

## Find matching parenthesis in text: `%`

----------------------

## Go to start of the line: `0`
## Go to end of line: `$`

----------------------

## To find next occurence of word under cursor: `*`
## To find previous occurence of word under cursor: `#`

----------------------

## Go to beggining of text file: `gg`
## Go to end of text file: `G`
## Go to specific line: `<number>G`

----------------------

## Search for a word in the text: `\<word>`
## Go to next occurence of word: `n`
## Go to previous occurrence of word: `N`

----------------------


## Insert new line next: `o`
## Insert new line previously: `O`



| Address (Before)  | Value (Before)  | Address (After) | Value (After) |
| -----------------:|:---------------:|:---------------:|:-------------:|
| 0x400b028         | 0x00000022      | 0x400b028       | **0x00000032**|
| 0x400b024         | 0x400b611c      | 0x400b024       | 0x400b611c    |
| 0x400b020         | 0x400b512c      | 0x400b020       | 0x400b512c    |
| 0x400b01c         | 0x00000d12      | 0x400b01c       | 0x00000d12    |
| 0x400b018         | 0x00000014      | 0x400b018       | 0x00000014    |
| 0x400b014         | 0x400b511c      | 0x400b014       | 0x400b511c    |
| 0x400b010         | 0x400b601c      | 0x400b010       | 0x400b601c    |
| 0x400b00c         | 0x00000022      | 0x400b00c       |  Anything     |
| 0x400b008         | 0x00000013      | 0x400b008       |  Anything     |
| 0x400b004         | 0x400b601c      | 0x400b004       | 0x400b601c    |
| 0x400b000         | 0x400b511c      | 0x400b000       | 0x400b511c    |
| 0x400affc         | 0x00000013      | 0x400affc       | **0x00000032**|
| 0x400aff8         | 0x0000001B      | 0x400aff8       | 0x0000001B    |
| 0x400aff4         | 0x400b601c      | 0x400aff4       | 0x400b601c    |
| 0x400aff0         | 0x00000014      | 0x400aff0       | 0x00000014    |
| 0x400afec         | 0x0a0bc11d      | 0x400afec       | 0x0a0bc11d    |
| 0x400afe8         | 0x400b511d      | 0x400afe8       | 0x400b511d    |
| 0x400afe4         | 0x0000001B      | 0x400afe4       | 0x0000001B    |


 
