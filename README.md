# All You Need To Know About Javascript Arrays

## Array Methods Cheatsheet
```javascript
[1, 2, 3].length;                             // 3
[1, 2, 3].push(4);                            // [1, 2, 3,4] *
[1, 2, 3].unshift(0);                         // [0, 1, 2, 3] *
[1, 2, 3].pop();                              // [1, 2]  *
[1, 2, 3].shift();                            // [2, 3] *
[1, 2, 3].at(2);                              // 3
[1, 2, 3].indexOf(3);                         // 2
[1, 2, 3].includes(3);                        // true
[1, 2, 3].map(num => Math.pow(num, 2));       // [1, 4, 9]
[1, 2, 3].filter(num => num % 2);             // [1, 3] 
[1, 2, 3].every(num => num > 1) ;             // false
[1, 2, 3].some(num => num === 3);             // true
[1, 2, 3].fill(10);                           // [10, 10, 10]
[1, 2, 3].reduce((acc, num) => acc + num, 0); // 6
[1, 2, 3].concat([4, 5]);                     // [1, 2, 3, 4, 5]
[1, 2, 3].reverse();                          // [3, 2, 1] 
[1, 2, 3].sort()
[1, 2, 3].join("-");                          // "1- 2- 3"
[1, 2, [3]].flat();                           // [1, 2, 3]
[1, 2, 3].find((num, i) => i === 1) ;         // 2
[1, 2, 3].findIndex(num => num === 2);        // 1
[1, 2, 3].toString();                         // 1, 2, 3
[1, 2, 3].slice(1, 3) ;                       // [2,3]
[1, 2, 3].splice(1, 0, 2, 3);                 // [1, 2, 3, 4]
Array.isArray("[1,2,3]");                     // false
Array.from("123");                            // ["1", "2", "3"]          
```