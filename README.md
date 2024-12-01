We use a sliding window concept with pointers left and right to iterate the string.
Using Hashmap we are counting the frequency
If the window contains exactly two distinct characters and their frequencies are equal, the current substring is a valid balanced substring.
The program keeps track of the longest balanced substrings and stores them in a list


Time Complexity:
O(n)
Space Complexity
O(1)