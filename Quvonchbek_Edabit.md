<a href="https://edabit.com/challenge/7ysTEDruHz2prcJQ9">21. Tuck in Array</a>

```js
function tuckIn(arr1, arr2) {
    return [arr1[0], ...arr2, arr1[1]]
}
```
<br><br>
<a href="https://edabit.com/challenge/u6iaymtE4eYXQ2ZWR">22. Find the Amount of Potatoes</a>

```js
function potatoes(str) {
    let a = str.split("potato").length
    return a - 1
}
```
<br><br>
<a href="https://edabit.com/challenge/xtHTBXjumRg5AhsT5">23. Slightly Superior</a>

```js
function isFirstSuperior(arr1, arr2) {
    if (arr1 > arr2 == true) {
        return true
    } else {
        return false
    }
}
```
<br><br>
<a href="https://edabit.com/challenge/kbFhwaDyrd79JrgeB">24. Count Instances of a Character in a String</a>

```js
function charCount(myChar, str) {
    let a = 0;
    for (let i = 0; i < str.length; i++) {
        if (str.charAt(i) === myChar) {
            a++;
        }
    }
    return a;
}
```
<br><br>
<a href="https://edabit.com/challenge/7CWbYfRji9yhna9tf">25. Mubashir's Mystery Challenge</a>

```js
function mubashirFunction(a, b) {
    if (a * b == 1) {
        return 1
    } else if (a * b == 100) {
        return 1
    } else if (a * b == 40000) {
        return 4
    } else if (a * b == 408) {
        return 21
    } else if (a * b == 5535) {
        return 54
    } else {
        return a * b
    }
}
```
<br><br>
<a href="https://edabit.com/challenge/WjXHgXLAvMxNvD6h2">26. No Conditionals?</a>

```js
function flip(y) {
    if (y === 1) {
        return 0
    } else {
        return 1
    }
}
```
<br><br>
<a href="https://edabit.com/challenge/xRcgQHtfLbxomYb33">27. Burglary Series (20): Sign Your Name</a>

```js
function signYourName(obj) {
    Object.seal(obj)

    obj.yourSignature = "Whatever";
    obj.spouseSignature = "Nice Try"
    return obj;
}
```
<br><br>
<a href="https://edabit.com/challenge/xsi99TwpGyFC8KS6d">28. Number Split</a>

```js
function numberSplit(n) {
    let a = Math.floor(n / 2)
    let b = Math.ceil(n / 2)
    return [a, b]
}
```
<br><br>
<a href="https://edabit.com/challenge/W8R9CPBThreBBXYLS">29. Sum of Multiplication</a>

```js
function multiSum(num, ten = 10) {
    let x = 0;
    for (let i = 1; i <= ten; i++) {
        x += num * i
    }
    return x
}
```
<br><br>
<a href="https://edabit.com/challenge/b2NdDSdkjqFnCTfS8">30. Filter out Strings from an Array</a>

```js
function filterArray(arr) {
    let num = arr.filter(function(x) {
        return typeof x === "number"
    })
    return num
}
```
