# finding-the-avg
12.Write a python program to find the average of the list of the numbers entered through
Keyboard.

n=int(input("Enter the Limit "))
s=0
for i in range (1,n+1):
    print("Enter ",i,end='')
    a=int(input("th number : "))
    s=s+a
    avg=s/n
    print("The sum of entered numbers : ",s)
    print("The average of entered numbers : ",avg)

Output:
Enter the Limit 4
Enter  1th number : 5
The sum of entered numbers :  5
The average of entered numbers :  1.25
Enter  2th number : 4
The sum of entered numbers :  9
The average of entered numbers :  2.25
Enter  3th number : 8
The sum of entered numbers :  17
The average of entered numbers :  4.25
Enter  4th number : 3
The sum of entered numbers :  20
The average of entered numbers :  5.0
