# Checkpoint-Algorithms-and-its-elements

This is an algorithm that read a sentence, which ends with a point, character by character and determine:
    #The length of the sentence (the number of characters).
    #The number of words in the sentence (assuming that the words are separated by a single space).
    #The number of vowels in the sentence.

I started by defining a suitable Algorithm name as: sentence_element_checking
>> 1. Declare and initilize a counter varibales and string variable to store character, word, space, increment, vowel and length.
>> 2 .Read the input sentence from the user.
>> 3. Iterate through each word in the sentence.
>> 4. While the condition (counter i < sentence length) is True.
>> 5. Check for word separation (space character) using a IF_ELSE_END_IF and increment space_count.
>> 6. For each space, increment sapce count otherwise increment character_length counter.
>> 7. Addtionally, check if the character is vowel. With SWITCH_END_SWITCH, check if it's a vowel and increment vowel_count.
>> 8. Increment counter i by 1 on every iteration
>> 9. End loop when (counter i < sentence length) is False
>> 10. Increment space count by 1 to account for the last word.
>> 11. Display the results - char count, word count, and vowel count.

 
