# program-3c
# 🧪 C Programming Lab
## 📘 Experiment No: 3c
### 🔹
**Date:** 5/3/2026  
**Name:** Sivakarthikeyan.V
**Register No:** 25017090 

---

## 🎯 AIM
To write a C program to read the elements of an array and print the first element of each row.
---

## 🧠 ALGORITHM
1.Get an array as input from the user.
2.print the first element of each row using for loop and index positions of the array elements.

---

## 💻 PROGRAM

```
#include <stdio.h>

int main()
{
    int n;
    
    scanf("%d",&n);
    int a[n][n];
    for(int i=0;i<n;i++)
    {
       for(int j=0;j<n;j++)
       {
        scanf("%d",&a[i][j]);
       }
    }
        for(int i=0;i<n;i++)
        printf("a[%d][0] is %d\n",i,a[i][0]);

    return 0;
}

```

## 🖼️ OUTPUT SCREENSHOT

<img width="816" height="342" alt="image" src="https://github.com/user-attachments/assets/775d6772-4ae7-4551-87e1-a33276b633b6" />

---

## ✅ RESULT
:Thus the c program to get an array as input and print the first element of each row is executed successfully.
