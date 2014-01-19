JQuery Shuffle Text 1.0
===========

### [Live Demo](http://www.anthonydupont.be/lab/ShuffleText)
JQuery Shuffle Text is a **lightweight** JQuery plugin able to shuffle any of your text content.
Easy to use, it offers a **set of options** to customize it...

**Note:**
Be aware this plugin is efficient with **small text content**. Don't use it with long paragraphs for example.
How to use it ?
-------------------------
To use **JQuery Shuffle Text** you need to target the content you want to shuffle and pass the output content to the function.

```js
    $("#myTarget").shuffleText("My output text");
```
Options
-------------------------
**JQuery Shuffle Text** offers a set of options to customize it:

+ **frames**   : The duration in milliseconds of the shuffle for each letter - *Default:* _**40**_
+ **maxSpeed** : The maximum duration of the global shuffle - *Default:* _**1000**_
+ **amount**   : The number of shuffle to do for each letter - *Default:* _**3**_
+ **complete** : Something to do when the shuffle is completed - *Default:* _**null**_

```js
    $("#myTarget").shuffleText("My output text", {
        frames : 30,
        maxSpeed : 2500,
        amount : 4,
        complete : function(){
            // Do something
        }
    });
```
Copyright
-------------------------
**JQuery Shuffle Text** is created by [Anthony Du Pont](http://www.twitter.com/Anthodpnt) and is completely **free for commercial use**.

**Notes**: Any problem to use this plugin ? Please [contact me](mailto:antho.dpnt@gmail.com).

If you **enjoy it**, please **share it** ;).