---
layout: post
title: "Operational vs Denotational"
date: 2018-10-16
tags:
image:
---
> The question of language is not functional vs imperative.  Rather Operational Semantic vs Denotational Semantic.

<!--more-->

I am trying to evaluate GO language for a project I am interested in.    It appears that there are some "go gotcha" constructs that one needs to be aware of when programming in go language.   

A useful blog post on the topic is: [How to avoid Go gotchas](https://divan.github.io/posts/avoid_gotchas/).   The intersting part is:

>Remember, “gotchas are .. valid constructs .. but is counter-intuitive”? That is it. You have only two options:
>
>“fix” the language
>fix the intuition
>Second is actually would be better seen as build the intuition. Once you have a clear mental image of how slices or interfaces work under the hood, it’s almost impossible to run into those mistakes.
>
>So, it worked for me and probably will work for others. That’s why I decided to gather that basic knowledge of some Go internals in this post and help people to build the intuition about an in-memory representation of different things.

This demonstrates the fundamental problem with programming languages that are defined by their operational semantic.    To make sense of a code you need to have a "clear mental" image of **HOW**
the program runs not **WHAT**, or the meaning of the instruction. 

Conal Elliot's [presentation](https://www.youtube.com/embed/teRC_Lf61Gw) covers the topic more in depth.
