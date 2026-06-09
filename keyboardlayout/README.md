# Layout motivations
I came from 2.5 years of using Colemak-Dh and a few months of using Graphite. Then I started creating my own keyboard layout that could better meet my needs by taking what I liked from both of the previous layouts. 

After about a year of experimenting with my own layout, I put what I had into Cyanophage's Playground to see how it scored, and used it as a guide to optimize it. 
This has resulted in two versions, where Monium_t is a type optimized layout that in many cases uses the solutions that helps its score, but not always, - and Monium_V which is closer to what I had going earlier on which is more VIM/Helix motion friendly. 

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

# Monium_t V1.1 (type optimized)
```
v g c w q  / f o u y
h s r f j  x n a e i
b m d l z  ; p , . k
```
<img width="1042" height="801" alt="image" src="https://github.com/user-attachments/assets/8461d997-c59f-40dd-bad1-ef8f15a70fbb" />
https://cyanophage.github.io/playground.html?layout=vgcwq%2Ffouy-hsrtjxnaei%3Dbmdlz%3Bp%2C.k%5C%27&mode=ergo&lan=english&thumb=l

## Ranking
Word effort 397.61, rank #4 (rank #1 among non-e/r mods).
Total word effort 914.8

## Reasons to hate Monium_t 
- Not good for VIM motions, needs to be walked around by using a navigation layer.

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
