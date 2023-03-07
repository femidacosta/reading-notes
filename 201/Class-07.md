Describe and Define

- Constructor functions
- JavaScript "prototypal inheritance"
- HTML ```<table>``` tag structure and usage

constructor function 
an object that is self replicating 

```
unction CookieStore(name, minCust, maxCust, avgCookie){ 
  this.name = name; 
  this.minCust = minCust; 
  this.maxCust = maxCust; 
  this.avgCookie = avgCookie; 
} 
CookieStore.prototype.getAvgCookieCount = function() { 
  console.log('some random number'); 
}; 
const seattle = new CookieStore('seattle', 15, 40, 6.3); 
const otherStore = new CookieStore('otherStore', 10, 30, 2.3); 
const anotherCookieStore = new CookieStore('anotherCookieStore', 5, 45, 3.3); 
const stores = [seattle, otherStore, anotherCookieStore];
```

this.name
//( the name that belongs (=) to 'this cookie store' 
prototype means 
everything else that gets created comes off the first prototype.

NEW CODE AFTER WE HAVE ADDED METHODS AND PROTOTYPES AND FUNCTIONS 