# palindrome- in python
#Approach-1
n = input()
if n == n[::-1]:
  print("Palindrome")
else:
  print("Not a Palindrome")
  
#Approach-2
def isPalindrome(s):
    return s == s[::-1]
s = "malayalam"
ans = isPalindrome(s)
if ans:
    print("Yes")
else:
    print("No")
