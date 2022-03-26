---
layout: post
title:  "Creating a programming language"
date:   2021-07-24 00:00:00 +0600
categories: tech-talk
---

When I first started programming, I was thrilled by the complex engineering of a programming language. Along the way, I came across several programming languages, C, Assembly, Python, JavaScript, MATLAB, and many more. But never did I think that I would be making one myself.

I started working with chaScript a few weeks ago. The whole thing is written in TypeScript, which itself was a new experience for me. I have worked with TypeScript before in Angular projects, but never in a standalone project. It mimics a LISP like-syntax and has features like math operations, variable declaration, conditional statement, and loop. Also, I got to make my first CLI app, which runs all the chaScript programs from the terminal.

It may sound daunting at first, but making a programming language, at least a simple one is not that hard. Once I got the hang of tokenizing, parsing, creating an abstract syntax tree (AST), and evaluating the AST, there's nothing much to it. Also, shout-out to Steve Kinney's dropbear, which was a constant inspiration along the way.

It may not have any practical use, but it was a fun and educative experience nonetheless.
<br>
<br>
<iframe
    width="100%"
    height="360"
    src="https://www.youtube.com/embed/vLUVsYFBLBc"
    frameborder="0"
    allow="autoplay; encrypted-media"
>
</iframe>
<br>
P.S. While making this, I didn't know there already exists something called chaScript. A friend of mine pointed it out after seeing the project.