
1. Introduction
2. Occurrance
```

let str = 'HelloWorld';

let occurranceOfString = {};

for (let char of str) {
if (occurranceOfString[char]) {
occurranceOfString[char]++;
} else {
occurranceOfString[char] = 1;
}
}
console.log(occurranceOfString);

```
2.Reverse string withut using inbuilt method
```

let reverseString = '';

for (let i = str.length - 1; i >= 0; i--) {
reverseString += str[i];
}
console.log(reverseString);

```
3. Merge array like a,b,a,b,a,b
```

const a = [45, 8485, 77, 6, 46];
const b = [78, 5, 1, 3, 55, 99];

const result = [];
const checkingMaxLength = Math.max(a.length, b.length);

for (let i = 0; i < checkingMaxLength; i++) {
if (i < a.length) {
result.push(a[i]);
}
if (i < b.length) {
result.push(b[i]);
}
}
console.log(result);

```
4. Scope of variables
5. why we are using this keyword? compare it with arrow and normal function
6. Explain map filter foreach
7. call bind apply
8. Types of Promises
9. Promises
10. Promise all
11. Is Javvascript is singlethreaded? with explain?
12. how eventloop is works?
13. Reduce method?
14. Dom vs Virtual Dom
15. Hooks in ReactJS
16. if render once what you will do?
17. explain lifecycle method in functional?
18. Usecallback vs useMemo
19. useReduces
20. UseRef
21. Child to parent how will do?
22. Implement parent to child?
23. TodoList implement.

