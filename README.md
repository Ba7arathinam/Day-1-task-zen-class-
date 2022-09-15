1. Difference between HTTP1.1 vs HTTP2

HTTP stands for hypertext transfer protocol and it is used in client server communication.By using HTTP user sends the request to the server & the server sends the response to the user.There are several stages of development of HTTP but we will focus mainly on HTTP1.1 which was created in 1997  and the new one is HTTP2 which was created in 2015

              HTTP1.1                                        
  1.it works on the textual format.                    
  
  2.There is head of line blocking that blocks all the requests behind it until it doesn’t
  get its all resources
  3.It uses requests resource Inlining for use getting multiple pages
  4.It compresses data by itself
  
             HTTP2
 1. It works on the binary protocol.
 2.It allows multiplexing so one TCP(Transmission Control Protocol) connection is required for multiple requests
 3.It uses PUSH frame by server that collects all multiple pages
 4.It uses HPACK for data compression
 
 
 2.Objects and its internal representation in Javascript
 
 Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types)
Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types,in the form of “key:value” pairs.These keys can be variables or functions and are called properties and methods,respectively,in the context of an object.
