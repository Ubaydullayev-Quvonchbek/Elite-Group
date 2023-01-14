<a href="https://edabit.com/challenge/vvuAkYEAArrZvmp6X">1.Bitwise Operations</a>

```js

function bitwiseAND(n1, n2) {
	return n1 & n2
}

function bitwiseOR(n1, n2) {
	return n1 | n2
}

function bitwiseXOR(n1, n2) {
	return n1 ^ n2
}

```
<a href="https://edabit.com/challenge/4gzDuDkompAqujpRi">2.Add up the Numbers from a Single Number</a>

```js
function addUp(num) {
	let sum = 0;
	for(let i = 1; i <= num; i++ ){
		sum += i ;
	}
	return sum;
}
```
<a href="https://edabit.com/challenge/tYHkTdFrEmWfxpPKF">3.Matchstick Houses</a>

```js
function matchHouses(step) {
	if(step == 0){
		return 0
	}
	return step*5+1
}
```
<a href="https://edabit.com/challenge/Gpy2qSFnfhGJnWMMj">9.Check if One Array can be Nested in Another</a>

```js
function canNest(arr1, arr2) {
	return(Math.min(...arr1) > Math.min(...arr2) &&
				Math.max(...arr1) < Math.max(...arr2));
}
```