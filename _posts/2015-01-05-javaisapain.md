---
layout: post
title:  "CS 3: Arraylist"
date:   2015-01-05 00:00:00
categories: compsci
---

The only reason I am writing this post is because it is required for my CS course, the non-challengeness of which I did not sign up for.  So, OK, Java Arraylists.

A Java arraylist is a dynamically allocating list.  It is defined by the following:
``` java
List<List> list = new ArrayList<List>();  
// or
ArrayList<ArrayList> list1 = new ArrayList<ArrayList>();
```

Unlike a static array (defined like `T[]`), an `ArrayList` or `List` are dynamic, meaning that they can change size after initialization.  That's just great, no?

Oh, and there's virtually no difference between and `ArrayList` and a `List`, but that the `ArrayList` is polymorphically superior to the `List` (aka a superclass) that allow use of both the `List` class and the static array methods.  (Why, Java, why...... decreasing production for misanthropic confusion.)

-----------------------------------------------------
Alright, I'm done here.  See you next month.

smo-key :bear:
