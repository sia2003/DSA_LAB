# DSA_LAB task # 1
def isPalindrome(s):
	return s == s[::-1]



s = input("ENTER A STRING : \n")
ans = isPalindrome(s)

if ans:
	print("IT'S A PALINDROME")
else:
	print("IT'S NOT A PALINDROME")
