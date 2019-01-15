# python-things
What I learned in experience, and don't want to forget.

## Matplotlib
- animation
- sent font to write korean words

## Pandas
- groupby
- transform

## Multitasking
- Threading(perform better at shallow but wide ranged task)
- Build Threads by for loop. each allocating a job. 
- Multiprocessing(perform better at complicated and slightly wide ranged task)
- using nohub(using terminal to allocate tasks to each processor)

## Re (Regular Expression)
https://www.youtube.com/watch?v=sa-TUpSx1JA  
https://www.youtube.com/watch?v=sZyAn2TW7GY  
- How to use symbols to indicate certain patterns
- (group), [range], [^not range], \d(opposite is \D), \b(opposite is \B),.etc
- *(0~), +(1~), ?(0 or 1), ^(beginning of string(line)), $(end of string(line))
- using groups to indicate that certain part of the string I want.
- ex) www.naver.com, www.google.com
- (\b{3})\.([a-zA-Z]+)(\.\b{3}) each group is group1($1), group2($2), group3($3)
- (be aware that in README.md, '\ .' is just ' .')
- you could replace or parse only that group by using $2

## lang-detect
- language detector

## translate
- Naver API or google translate

## Tokenizer (Konlpy & Khaiii & nltk)
- Konlpy.tag --> Kkma, Okt  
  
'always learning!'
