## exercise website https://regex101.com/

## quantifier
?   # 0 or 1
*   # 0 or more
+   # 1 or more
{n,m} / {n} / {n,}  # n to m
(ab)+  # ab one or more
## operator
(cat|dog)  # or operator
() # group / auto-capture group / auto-named group (from left to right start from 1) 
(?<name>expression) # named group
(?"name"expression) # named group
(?:expression) # non-capturing group/non-named group

## character classes
[abc]+  
[a-zA-Z0-9]
[^0-9]
[^0-9] # non-(0-9)

## meta-charactor
\d  number
\w  words/number/underscore
\s  space\tab(Tab)/newline(\n)
\D non-number
\W non-words
\S non-space
. non newline (non \n)
^  
$

## 
1 (?=pattern) # positive lookahead
  a(?=bc) # a followed by bc (abc)

2 (?<=pattern) #positive lookbehind
  (?<=bc)a     # a preceded by bc (bca)
3 (?!=pattern) #negative lookahead
  a(?!bc)      # a not followed by bc a(non-bc)
4 (?!<=pattern) #negative lookbehind
  (?!<=bc)a    # a not preceded by bc (non-bc)a