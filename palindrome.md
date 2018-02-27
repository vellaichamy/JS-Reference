/**
 * Given a string, return true if the string is a palindrome, or false if it is not.
 * NOTE: Do include spaces and puntuation in determining if the string is a palindrome
 *
 * Definition of Palindrome:
 * Palindromes are strings that form the same word if they're reversed.
 *
 * Examples:
 *   palindrome('abba') === true
 *   palindrome('abcdefgh') === false
 */

/**
 * Solution #1
 *
 * @method palindrome_1
 * @param  {string}     str The string to verify for it being a palindrome
 * @return {boolean}        Whether or not the string is a palindrome
 */
const palindrome_1 = str =>
  str
    .split('')
    .reverse()
    .join('') === str;

/**
 * Solution #2
 *
 * @method palindrome_2
 * @param  {string}     str The string to verify for it being a palindrome
 * @return {boolean}        Whether or not the string is a palindrome
 */
const palindrome_2 = str => str.split('').every((char, idx) => char === str[str.length - idx - 1]);

export default palindrome_2;
