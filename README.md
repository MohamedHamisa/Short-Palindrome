# Short-Palindrome

Consider a string, s, of n lowercase English letters where each character, si (0 <= i < n), denotes the letter at index i in s. We define an (a,b,c,d) palindromic tuple of s to be a sequence of indices in s satisfying the following criteria:

sa = sd, meaning the characters located at indices a and b are the same.

sb = sc, meaning the characters located at indices b and c are the same.

0 <= a < b < c < d < |s|, meaning that a, b, c, and d are ascending in value and are valid indices within string s.


Given s, find and print the number of (a,b,c,d) tuples satisfying the above conditions. As this value can be quite large, print it modulo (10^9 + 7).
