# Difference Between a Framework and a Library

Developers often use the terms **framework** and **library** alternatively but many of them don't know the differences between the two. In today's article, we'll discuss them and I hope this will clear your concepts between the two.

## What is a framework?
According to Wikipedia:

"In computer programming, a software framework is an abstraction in which software, providing generic functionality, can be selectively changed by additional user-written code, thus providing application-specific software. It provides a standard way to build and deploy applications and is a universal, reusable software environment that provides particular functionality as part of a larger software platform to facilitate the development of software applications, products, and solutions. Software frameworks may include support programs, compilers, code libraries, toolsets, and application programming interfaces (APIs) that bring together all the different components to enable the development of a project or system."

In simple words, a framework is some code written by some developers to solve some problems other developers face while building applications. But the main thing is that your applications are under the control of the framework and are limited to it.

### Resources-
Check out the following useful resources for creating your own JavaScript framework:

- [Building A JavaScript Framework](https://s3.amazonaws.com/dailyjs/files/build-a-javascript-framework.pdf)
- [How to Improve Your JavaScript Skills by Writing Your Own Web Development Framework](https://www.freecodecamp.org/news/how-to-improve-your-javascript-skills-by-writing-your-own-web-development-framework-eed2226f190/)
- [Learning JavaScript by building a UI framework from scratch](https://dev.to/carlmungazi/learning-javascript-by-building-a-ui-framework-from-scratch-1767)

> **Some examples of JavaScript frameworks are - Angular.js, Vue.js, etc.**

---

## What is a library?
According to Wikipedia:

"In computer science, a library is a collection of non-volatile resources used by computer programs, often for software development. These may include configuration data, documentation, help data, message templates, pre-written code and subroutines, classes, values or type specifications."

Similar to a framework, a library is also some code written by some developers to solve some problems other developers face while building applications. But the main thing here is that your applications come under your control and are not limited to the library.

> **Some examples of JavaScript libraries are - React.js, jQuery, etc.**


### Example -
Let’s say you have a program written in [JavaScript](https://en.wikipedia.org/wiki/JavaScript) where you intend to work with numbers. You decide to keep your code **DRY (don’t repeat yourself)** and write some reusable functions like these:

```js
function getReverse(number) {
    let rev = 0;
    while(number > 0) {
        rev = (rev * 10) + (number % 10);
        number = number / 10;
    }
    return rev;
}

function checkEven(number) {
    if(number % 2 == 0) {
       return true;
    }
    return false;
}

function checkOdd(number) {
    if(number % 2 != 0) {
       return true;
    }
    return false;
}
```
**Congratulations.🎊 You have created a JavaScript library.**

---

## Key Differences
The technical distinction between a framework and a library relies on a term called **inversion of control**. 

When you use a library, you are in charge of the flow of the application. You are choosing when and where to call the library. When you use a framework, the framework is in charge of the flow. It provides some places for you to plug in your code, but it calls the code you plugged in as needed.

The difference whether it is a library or framework is whether or not there is an inversion of control.

In a conclusion:
- Frameworks and libraries are both code written by someone else that helps you perform some common tasks in a less verbose way.
- A framework inverts the control of the program. It tells the developer what they need. A library doesn’t. - The programmer calls the library where and when they need it.
- The degree of freedom a library or framework gives the developer will dictate how “opinionated” it is.

> Key differences are taken from this [article](https://www.freecodecamp.org/news/the-difference-between-a-framework-and-a-library-bd133054023f/).

### Understanding with Real-life example

Let us take a real-life example. Let's say that you're going to college and you're waiting for your cab driver. But suddenly you got a message that he'll be late by an hour. Now, you have only 10 mins left in your hand to reach college otherwise you'll miss your class and your college is 5kms away from your house.

Now, you won't start making a car or a vehicle. So, you'd choose some better options like finding some vehicles to drop you to college, and finally, you got one and you're on the way to college. Now you can't tell the driver to take the route you find as a shortcut because he won't listen to you. So, you're in control. The same happens while using a library. In short, limited but more useful.

Now, after reaching college you tell your cab driver to pick you up back after your college. You tell him a time. Now you're waiting outside for your cab driver 15 mins before the scheduled time. But you can't tell him now to give you some special attention by coming to the location right now without any delay. The same happens while using a framework. In short, user-friendly but more limited.

---

## Conclusion
Libraries and frameworks both are useful as they both help developers to make better software and applications.

I hope that this article has cleared your concepts between a framework and a library. If you have any questions or feedback, put them in the comments below. 

---

## Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊
