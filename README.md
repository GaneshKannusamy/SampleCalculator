SampleCalculator
1. Create a simple String calculator with a method signature:

Use the following method signature int Add(string numbers)

The method can take up to two numbers, separated by commas, and will return their sum. for example “” or “1” or “1,2” as inputs. (for an empty string it will return 0)

Example: 
     a. Input: Add("1,2")     Output: 3
     B. Input: Add("1,2,3")   Output: 6

2. Allow the Add method to handle an unknown amount of numbers

3. Allow the Add method to handle new lines between numbers (instead of commas).
the following input is ok: “1\n2,3” (will equal 6)
the following input is NOT ok: “1,\n” (not need to prove it - just clarifying)

4. Different Delimiters

Support different delimiters to change a delimiter, the beginning of the string will contain a separate line that looks like this: “//[delimiter]\n[numbers…]” for example “//;\n1;2” should return three where the default delimiter is ‘;’ . the first line is optional. all existing scenarios should still be supported

5. Negative Numbers

Calling Add with a negative number will throw an exception “negatives not allowed” - and the negative that was passed. if there are multiple negatives, show all of them in the exception message.
