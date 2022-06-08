# NUWE CHALLANGES



## NUWE CTF #1

>  Analizar el fichero con los registros de las peticiones HTTP, debemos saber qué cuenta se ha vulnerado.

### Background
Solved the challange using Atom(regular expressions) and an Online tool to decode the tokens


### Usage
In Atom:
ctrl + F
Activate regex expressions
search for 
```shell 
131.199.174.193 -  - ......................................................................................2
```
![image](https://user-images.githubusercontent.com/19478700/168062933-16d1c029-a75a-48eb-ba9c-fddbdc0739c8.png)


Copy token
```shell 
131.199.174.193 -  - [22/03/2022:18:03:02 UTC+2] "POST /login?token=RkxBR3tzM2M4cjNfbDBnfQ%3D%3D HTTP/1.1" 200 221
```
Input to online tool
```shell 
RkxBR3tzM2M4cjNfbDBnfQ
```
![image](https://user-images.githubusercontent.com/19478700/168066781-a4e96ff6-251f-4e49-9437-69da2cdce81b.png)
Output flag
>"FLAG{s3c8r3_l0g}"


## SmallestMinimum
BruteForce Algorithm, very slow.

![image](https://user-images.githubusercontent.com/19478700/167954013-f0a71219-524b-44f2-b902-ac9dd86e5d84.png)


![image](https://user-images.githubusercontent.com/19478700/167953954-571c9503-5e0b-4807-b9c6-165a6e705921.png)

## PalindromicNumbers
A palindromic number reads the same both ways. The largest palindrome made from the product of two 2-digit numbers is 9009 = 91 × 99.

Find the largest palindrome made from the product of two 3-digit numbers.
![image](https://user-images.githubusercontent.com/19478700/167953640-588ad675-469b-472f-9fb7-98fc7acc5c9e.png)
![image](https://user-images.githubusercontent.com/19478700/167953661-de22fbe3-8d41-47af-a2df-9ac2ab072418.png)


## TrianglePerimeter
If p is the perimeter of a right angle triangle with integral length sides, {a,b,c}, there are exactly three solutions for p = 120.

{20,48,52}, {24,45,51}, {30,40,50}

For which value of p ≤ 1000, is the number of solutions maximised?

NUWE CHALLANGE

![image](https://user-images.githubusercontent.com/19478700/167947383-ea3fafb7-2657-4fc2-bc2d-9c55084dc064.png)

![image](https://user-images.githubusercontent.com/19478700/167947436-116c6879-6ba4-4e24-84ba-437ee3b2ada8.png)






















## Reconocimientos 

- [The art of readme](https://github.com/hackergrrl/art-of-readme)
- [common-readme](https://github.com/hackergrrl/common-readme)
- [JWT - jwt.io](https://jwt.io)


## See more



## Contact info

> polgalvezsoriano@gmail.com || Pol Galvez Soriano

## License

[MIT](https://opensource.org/licenses/MIT)
