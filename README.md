#wap to write number of even odd numbers from list 
list_num=[1,2,3,4,5,6,7,8,9]
list_count = len(list(filter(lambda n : n%2 ==0, list_num)))
list_odd = len(list(filter(lambda n : n%2!=0, list_num)))
print ("even count : ", list_count)
print ("odd count : ", list_odd)
