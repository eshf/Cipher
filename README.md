# micCipher
Given some ciphertext and let qi denote the frequency of the ith letter of the alphabet in this ciphertext. In other words, qi = fi , where fi is simply the number of occurrences of the ith letter of the alphabet in the ciphertext and N is the length of the ciphertext.
If the key is k in a shift (Caesar) cipher, then pi should be roughly equal to qi+k for all i, because the ith letter is mapped to the (i + k)th letter. 
 
This program 
•	take a ciphertext file as input;
•	display MIC values for each key on the screen;
display the right key (i.e. the key that successfully decrypts the given ciphertext) on the screen; (Note that the MIC value that corresponds to the right key is smaller than 0.065.)
•	display a decrypted plaintext (message) on the screen;
•	handle any possible errors;
