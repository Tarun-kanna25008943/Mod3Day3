# EX-03 Program to Print the Second Element of an Array

## AIM:
To write a C program that reads n integer elements into an array and prints the second element of the array.

## ALGORITHM:

1. Start
2. Declare an integer variable num.
3. Read the number of elements (num) from the user.
4. Declare an integer array arr[num].
5. Use a for loop from i = 0 to i < num:
     a. Read each element and store it in arr[i].
7. Print the second element of the array using arr[1].
8. Stop

## PROGRAM:
```
#include <stdio.h>

int main()
{
    int num;
    printf("Enter the size of the array: ");
    scanf("%d",&num);
    int arr[num];
    printf("Enter the elements: ");
	for(int i = 0; i<num; i++)
    {
        scanf("%d",&arr[i]);
    }
    printf("The second element of the arry is: %d",arr[1]);
    return 0;
}
```

## OUTPUT:
<img width="667" height="152" alt="image" src="https://github.com/user-attachments/assets/b24ae800-d346-419a-8b9f-40f0ee948bad" />

## RESULT:
The program successfully reads n integer elements from the user and prints the second element of the array.
