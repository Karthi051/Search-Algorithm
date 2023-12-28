# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```
''' 
Program for linear search method to match the item in a list
Developed by:karthi keyan k
RegisterNumber:23013936
'''
a=eval(input())
b=sorted(a)
c=eval(input())
for i in b:
    if i==c:
        print(b)
        print("Element found at index: ",b.index(c))
        break
else:
    print(b)
    print("Element not found")


```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```
''' 
Program for linear search method to match the item in a list
Developed by:karthi keyan k
RegisterNumber:23013936
'''
a=eval(input())
b=sorted(a)
c=eval(input())
for i in b:
    if i==c:
        print(b)
        print("Element found at index: ",b.index(c))
        break
else:
    print(b)
    print("Element not found")




```
iii)	# Find the element in a list using Binary Search (recursive Method).
```
''' 
Program for linear search method to match the item in a list
Developed by:karthi keyan k
RegisterNumber:23013936
'''
a=eval(input())
b=sorted(a)
c=eval(input())
for i in b:
    if i==c:
        print(b)
        print("Element found at index: ",b.index(c))
        break
else:
    print(b)
    print("Element not found")




```
## Sample Input and Output

![image](https://github.com/Karthi051/Search-Algorithm/assets/148327224/15530b8e-93fc-45e2-869f-330e1e6dc5b4)

![image](https://github.com/Karthi051/Search-Algorithm/assets/148327224/7a86bdd0-7f55-4f7f-8035-43a11fdf615f)

![image](https://github.com/Karthi051/Search-Algorithm/assets/148327224/f0322156-31ea-4583-bf0a-dc3e05dbedb2)



## Result
Thus the linear search and binary search algorithm is implemented using python programming.
