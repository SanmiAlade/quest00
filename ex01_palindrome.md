Step 1
MyString = 'racecar'
reversedMyString = str(MyString) [: :-1]  # this method is called slicing 
if str(MyString) == reversedMyString:
    print('The string is a palindrome')
else:
    print('The string is not a palindrome')

  'The sting is not a palindrome' 


Step 2 
Time → O(n)

Space → O(n)

# I missed the case sensitivity. Racecar fails becase Racecar != racecaR
This method fails for spaces and punctuation aswell 

# A better apprach will be Two pointer method


step 3. 
I learned that a palindrome is a sequence that is the same forward and backward. i also learned the method of "slicing" which is used to reverse strings. i also learned that a string is not a palindrome if it has spaces or capital letters.

After reviewing my code with AI i learned that there is a difference between "it works" and "it works properly". 
That being said, slicing is not a bad way of checking if a string is a palindrome or not, there are more efficient ways of attaining the same goal. I was able to understand the difference between slicing and two pointer method. 
Furthermore i learned that two pointer method is a more formal programming structure that can be used to test multiple strings. slicing duplicates the string which in turn doubles the memory needed to complete the task.

Yes i can attempt to write a similar function.
