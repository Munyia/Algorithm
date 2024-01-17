# Character, Word, and Vowel Count Algorithm

This algorithm reads a sentence, counts the number of words, vowels, and characters, and displays the results.

## How to Use

1. **Input**: Provide a sentence as input to the algorithm.
2. **Output**: The algorithm will output the total number of words, vowels, and characters in the given sentence.

## Algorithm Description

### Variables:
- `sent: STRING` - Variable to store the input sentence.
- `first: INTEGER` - Variable to track the position in the sentence.
- `totalWords: INTEGER` - Variable to count the total words (initialized to 1 for the first word).
- `totalVowels: INTEGER` - Variable to count the total vowels.
- `totalChars: INTEGER` - Variable to count the total characters (initialized to 1 for the first character).

### Algorithm Steps:

1. Read the input sentence.
2. Iterate through each character in the sentence.
   - Count words whenever a space is encountered.
   - Increment the vowel count for each vowel (a, e, i, o, u).
   - Move to the next character in the sentence and increment the total character count.
3. Continue until the end of the sentence is reached.
4. Display the total word count, total vowel count, and total character count.

## Example Usage

```plaintext
Read(sent) // Example Input: "i have a lot to say but you can't hear them because you never listen to me or to my silences."
CharacterWordVowelCount(sent)
