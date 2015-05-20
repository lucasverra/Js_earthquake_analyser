# Js_earthquake_analyser
Given 4k lines of earthquake info, transform into an usable array of objects to use as input in system

["x, egipto, x,x,x,x,x,",
"x, budapest, x,x,x,x,x,"
"x, hong kong, x,x,x,x,x,",
"x, hong kong, x,x,x,x,x,"]
```
->

```{ 
  "egipto": 1,
  "budapest": 1,
  "hong kong": 2
}```
->

```[
  { text:"egipto", count:1},
  { text: "budapest", count: 1},
  { text: "hong kong", count: 2}
]




http://terremotos-coderhouse.rhcloud.com/


en la consola para graficar ->
```var obj1 = {text:"egipto", count:5};
var obj2 = { text: "budapest" , count: 23};
init([obj1,obj2]);
