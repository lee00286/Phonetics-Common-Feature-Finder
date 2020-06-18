# Phonetics Common Feature Finder

> Phonetics Common Feature Finder - the English Consonants and Vowels
> (c) Yena Lee, Jun. 2020
> - No part of this code may be reproduced without written authorization

## Description
This code searches for the common feature between consonants or vowels.
A number is assigned for each consonant and vowel for easier input.
The code will ask three questions to answer. 
Proper error-checking is not provided, so please read and type-in the input carefully.

## Chart of assigned numbers
|| =============================================== ||

||     CONSONANTS      ||||         VOWELS         ||

|| =============================================== ||

|| 1: p                |||| 1: i                   ||

|| 2: b                |||| 2: ɪ                   ||

|| 3: m                |||| 3: u                   ||

|| 4: f                |||| 4: ʊ                   ||

|| 5: v                |||| 5: e/ej                ||

|| 6: θ                |||| 6: ɛ                   ||

|| 7: ð                |||| 7: ə                   ||

|| 8: t                |||| 8: ʌ                   ||

|| 9: d                |||| 9: o/ow                ||

|| 10: n               |||| 10: ɔj                 ||

|| 11: s               |||| 11: ɔ                  ||

|| 12: z               |||| 12: æ                  ||

|| 13: l               |||| 13: aj                 ||

|| 14: r               |||| 14: aw                 ||

|| 15: ʃ               |||| 15: ɑ                  ||

|| 16: ʒ               ||||                        ||

|| 17: ʧ               ||||                        ||

|| 18: ʤ               ||||                        ||

|| 19: j               ||||                        ||

|| 20: k               ||||                        ||

|| 21: g               ||||                        ||

|| 22: ŋ               ||||                        ||

|| 23: w               ||||                        ||

|| 24: ʔ               ||||                        ||

|| 25: h               ||||                        ||

|| =============================================== ||

## Common features of Consonants
- Place of Articulation (Labial, Dental, Alveolar, Alveopalatal, Palatal, Velar, Glottal)
- Manner of Articulation (Stop, Nasal Stop, Fricative, Affricate, Liquid, Glide)
- Voicing (Voiced, Voiceless)

## Common features of Vowels
- Height of the Tongue (High, Mid, Low)
- Backness of the Tongue (Front, Central, Back)
- Tenseness of the Vocal Tract (Tensed, Laxed)
- Roundedness of the Lips (Rounded, Unrounded)
- Simple Vowels/Diphthong (Simple Vowel, Major Diphthong, Minor Diphthong)

## Notes
- This code is only for the English consonants and vowels
- Some features are excluded
  - e.g. "Lateral Liquid" and "Retroflex Liquid" are combined as "Liquid"
- Place of articulation for the consonant w is set as "Labial", instead of "Bilabial"
- Finding a common feature between consonants and vowels is not supported in this code

## How to compile and run the code
```
$> gcc commonFeatureFinder.c -o commonFeature
$> ./commonFeature (on Mac)
$> .\commonFeature.exe (on Windows)
```
