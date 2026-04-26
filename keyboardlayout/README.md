# Layout motivations
I came from 2.5 years of using Colemak-Dh and a few months of using Graphite. Then I started creating my own keyboard layout that could better meet my needs by taking what I liked from both of the previous layouts. 

After about a year of experimenting with my own layout, I put what I had into Cyanophage's Playground to see how it scored, and used it as a guide to optimize it. 
This has resulted in two versions, where Monium_t is a type optimized layout that in many cases uses the solutions that helps its score, but not always, - and Monium_V which is closer to what I had going earlier on which is more VIM/Helix motion friendly. 

<img width="1104" height="378" alt="Moosy Research Alphaheat image" src="https://github.com/user-attachments/assets/cda649e4-2252-435a-8bf3-ae001d8ad04c" />
https://sites.google.com/view/keyboards/tools/alphaheat

# Layout objectives
- Keep common OS and app keys (c (copy), v (paste), d (duplicate), s (save), z (undo) on the left keyboard so when using GUI apps the right hand do not need to leave the mouse.
- Get 'h' 'l' 'k' 'j' on the left keyboard to move between windows in MangoWC without taking the right hand from the mouse. 
- Maintain a somewhat sane layout for VIM/Helix motions
- Minimize 5th and 6th colomns to minimize seqential index finger travel over the 4th to 5th, etc. 
- Rolls

# Reasons to hate the Monium layouts 
- if you are coming from querty or similar, you will find you use your pinky and ring finger more, and this might be uncomfortable. 
- 'e-y' movement is horrible. 

# Observations
Monium_t was designed after Cyanophage's Playground scoring system to see how low I could take the layout I already was working on. 

While it scores better than Monium_v, so far, Monium_v which is closer to what I had previously has felt better for me. 
I will try using Monium_t for the next six months, and if I feel like it does not improve then I will go back to Monium_v, possibly with a version 2.0. 

# Monium_t V1.0 (type optimized)
```
v g c w z  q f o u y
h s t r k  x n a e i
b m d l j  ; p , . /
```
<img width="989" height="785" alt="image" src="https://github.com/user-attachments/assets/01fcb7d9-f0dd-4d6f-9e81-7781127b6f44" />
https://cyanophage.github.io/playground.html?layout=vgcwzqfouy-hstrkxnaei%27bmdlj%3Bp%2C.%2F%5C%5E&mode=ergo&lan=english&thumb=l  

## Ranking
Word effort 417.16, rank #5 (rank #1 among non-e/r mods).

Total word effort 898.5, rank #11 (rank #1 among non-e/r mods).

## Reasons to hate Monium_t 
- Less sane VIM/HELIX motion layout, but there are way worse.

## Reasons to like Monium_t 
- Meeh. 

# Monium_v V1.1 (VIM/HELIX optimized)
```
v g h w z  q f o u y
c s r t k  x n a e i 
b m d l j  ; p , . /
```
<img width="1253" height="994" alt="image" src="https://github.com/user-attachments/assets/a3a3f73f-caff-48fb-a54a-f28409c321e0" />
https://cyanophage.github.io/playground.html?layout=bwhlzqfouy-csrtkxnaei%27gvmdj%3Bp%2C.%2F%5C%5E&mode=ergo&lan=english&thumb=l

## Ranking
Word effort 417.16, rank #5 (rank #1 among non-e/r mods)

Total word effort 936.2, rank #17 (rank #6 among non-e/r mods)

## Reasons to hate Monium_v v1.1
- 'h-l' which in Vim-like editors are cursor left/right are scissored. The strain can be minimized by moving the index and middle finger together up and down. 

## Reasons to like Monium_v
- More sane VIM/Helix motions
- 'c' on pinky is less work.
- 'c-h', 'g-h', 'w-h', 's-h', 't-h' feels really good.
