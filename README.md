[Course Link](https://www.udemy.com/course/master-the-coding-interview-data-structures-algorithms)

[Programming in web - repl.it](https://replit.com/~)

# Big O Asymptotic Notation

## What is good code?
* 1 - Readable
* 2 - Scalable - Big O


```javascript
const nemo = ['nemo'];

function findNemo(array) {
  let t0 = performance.now();
  for(let i = 0; i < array.length; i++) {
    if(array[i] === 'nemo') console.log('Found NEMO');
  } 
  let t1 = performance.now();
  console.log('Call to find nemo took: ' + (t1-t0) + ' milliseconds');
}

findNemo(nemo); // O(n) ---> Linear Time

```


## Big O Complexity Chart
![](imgs/01.png)


## O(n)
![](imgs/02.png)

## O(1)
![](imgs/03.png)

