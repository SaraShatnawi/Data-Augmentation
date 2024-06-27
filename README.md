# Data Augmentation for Speech-Based Diacritic Restoration
Sara Shatnawi, Sawsan Alqahtani, Shady Shehata, Hanan Aldarmaki <br> 
Mohamed bin Zayed University of Artificial Intelligence, Abu Dhabi, UAE <br>
## Data Augmentation Rules 
### Replacement Rules
* Sukoon or Shaddah if they appear at the first letter of the word (i.e.,مْقعد ).
* Tanween if it appears in any letter except the last letter in the word.
* One of the two Shaddahs appearing on two contiguous characters (i.e.,مَقّعّد ).
* Any diacritic that is not Fatha or Damma appearing on Hamza on top (أ) at the beginning of a word (example of allowed variations, in this case, أَصبحَ or أُصبحَ ).
* Any diacritic that is not Kasra appearing on Hamza below Alef (إ), such as the word إلى.
* Any diacritic that is not Fatha before the tied T (ة) (i.e., the Arabic word مَدرَسَة).
* Any diacritic other than Fatha before the letter Alef of the following forms: ( ى ) or ( ا ).
* Stand-alone Shadda should be followed by another diacritic.

### Deletion Rules
* All diacritics are placed on characters, not in the Arabic alphabet.
* All diacritics applied to the following forms of Alef: Alef Madd (آ), Alef (ا), Maqsura (ى), and at the beginning of a word (Alef followed by the letter Lam) indicating the definiteness of a word (ال).
* Any additional diacritic for each letter, except if this additional diacritic accompanies Shaddah (i.e., each letter should have only one diacritic except in the case of Shaddah, which can be followed by an additional diacritic).
