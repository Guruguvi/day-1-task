README.md
1.Write a blog on Difference between HTTP1.1 vs HTTP2

ANS:

HTTP/1.1

       1. It use works on the textual format.
 
       2. There is head of line blocking that blocks all the
          requests behind it until it doesn’t get its all resources.
     
       3. It uses requests resource Inlining for use getting multiple pages
 
       4. It compresses data by itself.
HTTP/2

       1. It works on the binary protocol.

       2. It allows multiplexing so one TCP 
          connection is required for multiple requests.
    
       3. It uses PUSH frame by server that collects all multiple pages .

       4. It uses HPACK for data compression.
2.Write a blog about objects and its internal representation in Javascript

ANS:

Objects.

        * Objects in JavaScript may be defined as an unordered collection 
          of related data, of primitive 
                                 (or)
        * reference types, in the
          form of “key: value” pairs. 
 
        * These keys can be variables or functions
          and are called properties and methods, respectively, in the
          context of an object.
Internal properties in JavaScript.

        * Internal properties define the behavior of code as it
          executes but are not accessible via code. 
   
        * ECMAScript defines many internal properties for objects in 
          JavaScript. Internal properties are indicated by
          double-square-bracket notation.

 For example,
        * JavaScript function is an object and it has [[call]] property.
