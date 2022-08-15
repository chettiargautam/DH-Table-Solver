# DH-Table-Solver

Introduction

Given DH Table will have parameters [theta, alpha, r, d] for each (n,n+1) frame interaction, you can obtain the H(n,n+1) matrix and multiplying all of these matrices in the same order as their frame interactions will give you the resultant Transformation Solution.

DH Parameters
Theta is the rotation needed in the (n-1) frame in the Zn-1 direction to match the X axes.
Alpha is the rotation needed in the (n-1) frame in the Xn direction to match the Z axes.
R is the distance between the centres of the (n-1) and the (n) frame in the Xn direction.
D is the distance between the centres of the (n-1) and the (n) frame in the Zn-1 direction.

Instructions:
1) Generate the Frames according the rules of the Denavit-Hatenberg Convention and label them accordingly.
2)  From the rules mentioned above, generate the values for the DH Table between each (n-1,n)th frame. One example has been shown below.

![image](https://user-images.githubusercontent.com/65887524/184589688-1f7cfc97-ab2c-43a7-a657-fa7c76697e3b.png)

3) Generate a matrix as shown below of the same 

![image](https://user-images.githubusercontent.com/65887524/184589712-463dc529-7710-4743-b52e-e284870f26c1.png)

4) Till the part above you will have to manually solve, the part after this requires just entering variable values. Create a variable which holds the entire table values as shown
*Also ensure the order matches as follows[theta, alpha, r, d].
5) Start by creating symbolic variables.

![image](https://user-images.githubusercontent.com/65887524/184589738-f6083064-c04b-4e9c-bf43-cb7e3205d75f.png)

6) Create the matrix, preferred to convert everything to radian unless all values are numeric.

![image](https://user-images.githubusercontent.com/65887524/184589766-7a25372f-3ef3-4c9d-868f-43fece99189c.png)

7) Enter the matrix and angle type as 'r' in the DH_HTM() function, make sure to download all the functions mentioned for this to work.

![image](https://user-images.githubusercontent.com/65887524/184589781-c72d5437-d1d6-4067-9683-94fe7b59f48c.png)

8) Cheers!
