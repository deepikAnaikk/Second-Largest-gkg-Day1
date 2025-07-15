# Second-Largest-gkg
Explanation:
first: holds the largest number.

second: holds the second largest, distinct from first.

Traverse the array:

If the current number num is greater than first, update both first and second.

If it's less than first but greater than second, update second.

If no valid second largest exists, second remains -1.
