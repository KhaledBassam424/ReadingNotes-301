# Node.Js

There are two sayings about Node.Js in terms of defining the terminology:

1. It is a Javascript runtime built on Chrome’s V8 JavaScript engine. Where the

 runtime refers to the period of the last stage in which the code are excuted.

 2. it is an event-based  non-blocking, asynchronous I/O runtime 

 Let is talk about  *javascript v8 engine* which is used by node.js.

 it is open source javascript engine that runs in googlechrome and similar search engines.

 His main purpose is compiling your code language into the native machine language where it would be excuted there. and you get what you called for.

 we don't mean when we say node.js is built on v8engine that codes are excuted there.

 In summary Node.js is a program that we use on our computers to excute javascript.

 > which is better for your system Node Binaries or Version Manager? 

 version manager is better for your device because it allows you to install 
 
 multiple versions of Node and switch between them at will.


 > What distinguishes  Node.js from others is that is ha has excellent support for ECMAScript 2015 (ES6) and beyond.

  It also means that you don’t generally have to worry about compatibility issues — as you would if you were writing JavaScript that would run in different browsers.

   this means that you can write your JavaScript using the latest and most modern syntax. It also means that you don’t generally have to worry about compatibility issues — as you would if you were writing JavaScript that would run in different browsers. 

   to explain this point write this code which contains modern javascript functions:

   ```function upcase(strings, ...values) {
  return values.map(name => name[0].toUpperCase() + name.slice(1))
    .join(' ') + strings[2];
}

const person = {
  first: 'brendan',
  last: 'eich',
  age: 56,
  position: 'CEO of Brave Software',
};

const { first, last } = person;
const emoticon = [ ['┌', '('], ['˘', '⌣'], ['˘', ')', 'ʃ'] ];

console.log(
  upcase`${first} ${last} is the creator of JavaScript! ` + emoticon.flat().join('')
);
```

Save this code to a file called index.js and run it from your terminal using the command node index.js. You should see Brendan Eich is the creator of JavaScript! ┌(˘⌣˘)ʃ output to the terminal.


So, don't worry about compatibility issues.


