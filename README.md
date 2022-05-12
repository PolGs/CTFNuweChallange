# CTFNuweChallange

Found vulnerated account using find and replace and regular expressions:
![image](https://user-images.githubusercontent.com/19478700/168062933-16d1c029-a75a-48eb-ba9c-fddbdc0739c8.png)

Decoded JWT using online tool like cyberchef
![image](https://user-images.githubusercontent.com/19478700/168066781-a4e96ff6-251f-4e49-9437-69da2cdce81b.png)


131.199.174.193 -  - [22/03/2022:18:03:02 UTC+2] "POST /login?token=RkxBR3tzM2M4cjNfbDBnfQ%3D%3D HTTP/1.1" 200 221
RkxBR3tzM2M4cjNfbDBnfQ
### "FLAG{s3c8r3_l0g}"








# # CTFNuweChallange

>  Analizar el fichero con los registros de las peticiones HTTP, debemos saber qué cuenta se ha vulnerado.

## Background
Solved the challange using Atom(regular expressions) and an Online tool to decode the tokens


## Usage
In Atom:
ctrl + F
Activate regex expressions
search for 
>131.199.174.193 -  - ......................................................................................2
Copy token
> 131.199.174.193 -  - [22/03/2022:18:03:02 UTC+2] "POST /login?token=RkxBR3tzM2M4cjNfbDBnfQ%3D%3D HTTP/1.1" 200 221
Input to online tool
>RkxBR3tzM2M4cjNfbDBnfQ
Output flag
>"FLAG{s3c8r3_l0g}"
## Installation

```shell
      no installation needed
```

## Reconocimientos 

- [The art of readme](https://github.com/hackergrrl/art-of-readme)
- [common-readme](https://github.com/hackergrrl/common-readme)
- [JWT - jwt.io](https://jwt.io)


## See more



## Contact info

> polgalvezsoriano@gmail.com || Pol Galvez Soriano

## License

[MIT](https://opensource.org/licenses/MIT)
