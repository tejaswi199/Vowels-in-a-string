#Approach-1
s=input()
v="aeiouAEIOU"
for i in range(len(s)):
  if s[i] not in v:
    print("NO")
    break
else:
  print("Yes")

 #Approach-2 
s=input()
v="AEIOUaeiou"
for i in s:
  if i not in v:
    print("NO")
    break
else:
  print("YES")

#Approach-3
s=input()
v="AEIOUaeiou"
c=0
for i in range(len(s)):
  if s[i] in v:
    c=c+1 
if c==len(s):
  print("Yes")
else:
  print('No')

 #Approach-4 
s=input()
v="AEIOUaeiou"
c=0
for i in s:
  if i in v:
    c=c+1 
if c==len(s):
  print("Yes")
else:
  print('No')
  
