

text = input("enter a string: ")

cleaned = text.replace(" ", " ").lower()

if cleaned == cleaned[::-1]:
  print("it is a palindrome.")
else:
  print("it is not a palindrome.")
