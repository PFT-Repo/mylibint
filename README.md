# Mylibint

This a little example of a library made with TypeScript of four simple calculations.

##  Instalation

```javascript 
npm i mylibint
```
## Methods

```javascript 
getSum(a:number,b:number):number
```
to make additions for two numbers. 
returns in terminal a + b

```javascript 
getSubs(a:number,b:number):number
```
to make substractions for two numbers.
returns in terminal a - b

```javascript 
getMul(a:number,b:number):number
```
to make multiplication for two numbers.
returns in terminal a * b

```javascript 
getDiv(a:number,b:number):number
```
to divide two numbers.
returns in terminal a / b
pd: if you use a 0 as b, it will return a NaN.

## Usage
After installation:

```javascript 
import {Calculator} from 'mylibint';
let calculator = new Calculator;
//to see the result in terminal of addition
console.log(calculator.getSum(1,1));
```
## Further 

programasfulltech@gmail.com