---
layout: post
title: Sample blog post title
subtitle: Each post also has a subtitle
tags: [test]
comments: false
---

This is a demo post to show you how to write blog posts with markdown.  You could also [take 5 minutes to learn how to write in markdown here](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc. All the basics you'll need to get up and running.

**Here is some bold text**

*Here is some italic text*

***Here is some bold italic text***

Here is [a link to another site](https://www.wikipedia.org)

## Here is a secondary heading

### Here is a tertiary heading

Here's a useless table (fair warning, tables are kind of a pain in markdown):

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

How about an image (from an external site)?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
