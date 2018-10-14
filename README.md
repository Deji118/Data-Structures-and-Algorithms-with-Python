# Python-Basicss
The real basics of python, Data Structures and Algorithms
def binary(list, item):
 low=0
 high =len(list)-1
 while low<=high:
     mid=int((low+high)/2)
     guess=list[mid]
     if guess==item:
         return mid
     if guess<item:
      low=mid-1
      print(mid)
     if guess>item:
      high=mid+1
      print(mid)
 return none
