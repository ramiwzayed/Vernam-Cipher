# Vernam-Cipher(STREAM)

# How to use Vernam Cipher

ci = pi XOR ki

* C means binary digit of ciphertext

* P means binary digit of plaintext

* K  means binary digit of key

# Example 
C= P XOR K 
Encrypt the message M = 1110101010, given the key k = 1100110101
#### Encrypt Solution
1110101010
1100110101
Final Soulution after encypt >>> C = 0010011111

#### Dencrypt Solution
M = C XOR K 
0010011111
1100110101
M = 1110101010

Important point if the message had 20 digit and the key had 10 digit we should repeat the key 1 more time like this 
M = 10010100011101101001 20 digit 
K = 1110010011  10 digit 
K after repeating  = 11100100111110010011
