JQuery Shuffle Text 1.0
===========

JQuery Shuffle Text is a **lightweight** JQuery plugin able to shuffle any of your text content.
Easy to use, it offers a **set of options** to customize it...

**Note:**
Be aware this plugin is efficient with **small text content**. Don't use it with long paragraphs for example.

### [Live Demo](http://www.anthonydupont.be/lab/ShuffleText)
How to use it ?
-------------------------

To use **JQuery Shuffle Text** you need to target the content you want to shuffle and pass the output content to the function.

```js
    $("#myTarget").shuffleText("My output text");
```
Options
-------------------------

**JQuery Shuffle Text** offers a set of options to customize it:

+ **frames** : The duration in milliseconds of the shuffle for each letter - Default: **40**
+ **maxSpeed** : The maximum duration of the global shuffle - Default: **1000**
+ **amount** : The number of shuffle to do for each letter - Default: **3**
+ **complete** : The function to launch when the shuffle is completed - Default: **null**