# ng-conf 2016: Reactive Programming, changing the world at Netflix, Microsoft, Slack and beyond!

## Abstract

What's does a mouse drag event have in common with an Array of numbers?

The answer to this question may surprise you: they are both collections. This key insight holds the key to dramatically simplifying asynchronous programming in JavaScript. In this talk you will learn how you can use the familiar JavaScript Array#extras methods to create surprisingly expressive asynchronous programs. Using just a few functions, you will learn how to do the following:

- Declaratively build complex events out of simple events (ex. drag n' drop)
- Coordinate and sequence multiple Ajax requests
- Reactively update UIs in response to data changes
- Eliminate memory leaks caused by neglecting to unsubscribe from events
- Gracefully propagate and handle asynchronous exceptions

In this talk we'll be exploring the Reactive Extensions for JavaScript (RxJS) library which allows us to treat events as collections. We'll also contrast RxJS with Promises and other popular approaches to building asynchronous programs in JavaScript. We'll also dive into the future with RxJS with generators, ES7 asynchronous functions, and even query transformations.

We'll talk about how this approach was used at Netflix, Slack, and Microsoft with great success with solving such problems as asynchronous search via autocomplete, scrolling, and infrastructure such as multiplexed WebSockets.

## Resources

Slides:
- [ng-conf-2016.pdf](ng-conf-2016.pdf)

Getting Started:
- [reactivex.io](http://reactivex.io)
- [Taking Advantage of Observables in Angular 2 Part 1](http://blog.thoughtram.io/angular/2016/01/06/taking-advantage-of-observables-in-angular2.html)
- [Taking Advantage of Observables in Angular 2 Part 2](http://blog.thoughtram.io/angular/2016/01/07/taking-advantage-of-observables-in-angular2-pt2.html)
- [Node.js + RxJS on the Server](https://glebbahmutov.com/blog/node-server-with-rx-and-cycle/)

Libraries:
- [RxJS v5](https://github.com/ReactiveX/RxJS)
- [RxJS v4](https://github.com/Reactive-Extensions/RxJS)
- [ngrx](https://github.com/ngrx)
- [rx.angular.js](https://github.com/Reactive-Extensions/rx.angular.js)

Promises:
- [Cancellation Spec](https://github.com/promises-aplus/cancellation-spec)
- [Aborting a Fetch](https://github.com/whatwg/fetch/issues/27)

Object.observe:
- [Object.observe specification](https://github.com/arv/ecmascript-object-observe)
- [Object.observe being withdrawn](https://esdiscuss.org/topic/an-update-on-object-observe)

ECMA Observable:
- [ES Observable Spec](https://github.com/zenparsing/es-observable/)

Contact Us:
- [@mattpodwysocki](https://twitter.com/mattpodwysocki)
- [@ReactiveX](https://twitter.com/reactivex)

## LICENSE

The MIT License (MIT)

Copyright (c) 2016 Matthew Podwysocki

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
