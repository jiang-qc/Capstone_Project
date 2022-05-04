# Wordle Solver

Wordle is a word guessing game where the user must guess a 5 letter word within 6 guesses by guessing a single word at a time.  The player will then receive feedback on whether or not each letter in the word is:

1. Not in the word at all. (False prediction)
2. In the word, but not in the given position. (False position)
3. In the word, at the guessed position. (True prediction)

![title](Wordle.png)

There are two tasks in the coding challenge:


## Task 1: An English Wordle solver.

Given a list of acceptable words in "English_words.txt" (we're changing things up a bit, and giving you words of length *6*, instead of length 5), decide upon a strategy to choose the most likely solution. You are free to use any strategy you want.  

## Task 2: A Gitksan Wordle solver.

Gitksan is the language of the Gitxsan people of British Columbia. It belongs to the Tsimshianic language family, and has far fewer speakers than English.  The language is written using a modified version of the Latin alphabet, with both digraphs/trigraphs (two/three letters that represent one sound, like 'th' in English) and diacritics (accents or markings that change the meaning of the letter).  For example, "hl" is considered one letter, representing a single sound, as is <ins>k</ins>.  The letters used in Gitksan are as follow (sourced from : Gitksan, by Jason Brown, Henry Davis, Michael Schwan and Barbara Sennott). Thanks to the Gitksan Lab in the UBC department of Linguistics for providing the dictionary, and being very enthusiastic about this coding problem.

p
b
d
t
k
kw
<ins>k</ins>
gy
gw
<ins>g</ins>
g
ts
j
p'
t'
ky'
kw'
<ins>k</ins>'
ts'
tl'
m
n
s
x
xw
<ins>x</ins>
h
hl
y
w
l
'm
'n
'l
'y
'w
i
ii
ee
a
aa
oo
u
uu

Now, you will need to add an additional step of breaking your words into characters, and recalculating your statistics based on those letters.  'laaxw' ("trout") is not [l, a, a, x, w], but rather, [l, aa, xw].  You will have to modify your code so that it accepts lists of characters instead of words.  In the provided 'Gitksan5.txt' file, underlined characters are represented with a following underscore: _. So <ins>x</ins> is x_, <ins>k</ins>' is k_', etc.  You will have to determine your own way of segmenting the data to represent Gitksan letters.
    
Here are some hints and tips (courtesy of Michael Schwan in the Gitksan lab):
    
    * A sequence of something like k_' = ḵ'
      Underlines only apply to k g and x (phonetically, they represent a uvular version of their velar equivalent.  ELI5: your tongue is farther back in your mouth when you pronounce them.)

    * An apostrophe between two vowels is a glottal stop (like the sound in "uh-oh")
    
    * An apostrophe before m n l y or w is a "glottalized resonant" and goes before the resonant, so 'm 'n 'l 'y and 'w (no English equivalent, but it's a bit like a little cough or hiccough as you pronounce the sound)
    
    * An apostrophe after a stop or affricate is a glottalized obstruent (not necessarily ejective), p' t' ts' tl' k' ky' kw' ḵ' (again, no English equivalent, but they sound notably different from similar sounds in English).

    * Digraphs to look out for are xw kw gw ky gy ts hl, and kw ky and ts can be followed by an apostrophe (tl' is only ever glottalized. tl without apostrophe is just a sequence of t and l).  If you're interested, the "w" digraphs are prounounce with the lips rounded, and the "y" ones with the middle of the tongue raised towards the roof of the mouth).

    * Long vowels are also digraphs. e = short /e/, and ee = long /e:/
    
    
There may be instances where you have to make a choice in how a word is segmented, and it may impact your results slightly.  It would take a certain level of fluency in Gitksan to always get this correct, but don't worry - consistency is more important than 100% accuracy.
