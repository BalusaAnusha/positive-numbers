# positive-numbers
to give positive numbers as output

#list of numbers
list1=[-10,21,15,-22,77,44,83,72]
num=0

#using while loop
while(num<len(list1)):

  #checking condition
  if list1[num]>=0:
    print(list1[num],end=" ")
    
  #increment num
  num+=1
