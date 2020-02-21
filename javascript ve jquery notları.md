# javascript ve jquery notları

We will look at what the code on the right does
shortly, but for the moment note that:

- Each of the lines of code in gree n is a statement.
- The pink curly braces indicate the start and end of a code block. (Each code block could contain many more statements.)
- The cod e in purple determines which code should run (as you will see on p149).

```js
{
var today= new Date{);
var hourNow = today.getHours{) ;
var greeting;
if (hourNow > 18) {
greeting= 'Good evening';
}
else if (hourNow > 12) {
greeting= 'Good afternoon';
}
else if (hourNow > O) {
greeting 'Good morning';
}
else {
greeting 'Welcome';
}
document.write(greeting);
}
```

### JAVASCRIPT IS CASE SENSITIVE

JavaScript is case sensitive so hourNow means
something different to HourNow or HOURNOW.

## COMMENTS

'''js

/_ This script displays a greeting to the user based upon the current time. It is an example from JavaScript & jQuer y book _/

var today= new Date(); // Create a new date object
var hour Now = today.getHours(); //find the current hour
var greeting;

'''

> {

    JavaScript codeis **green**
    Multi-line comments are **pink**
    Single-line comments are **gray**

}
