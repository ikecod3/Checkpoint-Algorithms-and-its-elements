# Checkpoint-Algorithms-and-its-elements

This is an algorithm that read a sentence, which ends with a point, character by character and determine:
    #The length of the sentence (the number of characters).
    #The number of words in the sentence (assuming that the words are separated by a single space).
    #The number of vowels in the sentence.

I started by defining a suitable Algorithm name as: sentence_element_checking
>>Declare and initilize a counter varibales and string variable to store character, word, space, increment, vowel and length.
>> Read the input sentence from the user.
>> Iterate through each word in the sentence.
>> While the condition (counter i < sentence length) is True.
>> Check for word separation (space character) using a IF_ELSE_END_IF and increment space_count.
>> For each space, increment sapce count otherwise increment character_length counter.
>> Addtionally, check if the character is vowel. With SWITCH_END_SWITCH, check if it's a vowel and increment vowel_count.
>> Increment counter i by 1 on every iteration
>> End loop when (counter i < sentence length) is False
>> Increment space count by 1 to account for the last word.
>> Display the results - char count, word count, and vowel count.

 
