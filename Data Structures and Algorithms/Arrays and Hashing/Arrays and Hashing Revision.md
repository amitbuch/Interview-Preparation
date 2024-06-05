Memorizing and Techniques to be used with Arrays and Hashes Datastructures and Algorithms

1. Python arrays made of builtin or custom object types.

2. When an array is processed through for loop the time complexity is O (n) where n is the length.if there are nested loops it will be O(n^^2) : N squared.

3. In Python hashmaps are implemented with Dictionary {} object. Use DefaultDictionary type if you want to automatically create missing keys. Defaultdictionary type can take list as an argument but make sure you convert this list to a tuple (immutable) before usign it as a key in the dictionary.

4. with problems like find duplicates in a list or find the indices of elements that add upto a certain number, or find anagrams etc. use dictionaries and use the array element as key and their count as values. 

5. for finding anagrams in a list of strings, use the clever technique of defautdictionary and provide list of entire alphabet (a-z) as a key and keep appending the found strings.

6. Mentally rehearse the prefix and post fix array based solutions that are good techniques to find product of array elements exacept for itself.

7. Converting a list or array to a set remove duplicate elements. longest Consequtive sequence uses left neighbor and right neighbor to identify start and end of a sequence and then return the longest. use set to avoid repeating numbers.
