Aleksandr Pak

+ pakalex82@gmail.com
+ 998 90 316 2 791

Briefly: I am working as System Administrator in non-goverment organization. 

Skills: I am studying the JavaScript.

Education: Tashkent State Technical University, 1999 - 2003

Languages: English, pre-intermediate. Russian, fluent.

Find The Duplicated Number in a Consecutive Unsorted List, example of code:

```
function findDup( arr ){
 let result = [];
 let duplicateValue = 0;
  
  for (let str of arr) {
    if (!result.includes(str)) {
      result.push(str);
    } else {
      duplicateValue = duplicateValue + str;
    }
  }
  return duplicateValue;
}
```