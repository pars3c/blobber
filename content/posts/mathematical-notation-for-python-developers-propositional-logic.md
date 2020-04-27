---
template: post
title: Mathematical Notation for Python Developers | Propositional Logic
slug: mathematical-notation-for-python-developers-propositional-logic
draft: false
date: 2020-04-26T12:44:32.170Z
description: Learn Propositional Logic with the simplicity of Python.
category: "Education"
tags:
  - "Education"
  - "Technology"
  - "Python"
  - "Mathematics"
  - "Mathematical Notation"
---
<style>
iframe {
    margin: auto;
    max-width: 100%!important;
}
</style>


![Photo by [Bekky Bekks](https://unsplash.com/@bekky_bekks?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/9956/0*Dmz0oy4cfLT2-oGY)

## Introduction

As developers, we require to be always up to date with the new tech stack however we tend to forget the importance of the underlying structure in which new tech stacks are built-in.

I am not saying we are required to be ninjas at assembly or binary but a good understanding of how they work is necessary in order to progress as a developer. 

Learning **Propositional Logic** can help you understand how circuits work programming conditions, writing your code with mathematical notation amongst other things.

![Photo by [Laura Gilchrist](https://unsplash.com/@lauragilchristedu?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/8064/0*DlAJo0dvWvvAMRDE)

## Who Is This Article For

By now, you might be wondering: “Do I need to know Python or Binary to understand this article?”. You do not!

I made this article for anyone who is interested in learning mathematical notation.

## Propositional Logic



### AND | Conjunction

*AND expressions are denoted with the symbol *∧ .

a ∧ b = a and b

Both a and b must be true in order for an **AND** statement to be true or else it will always be false.

|1 ∧ 0 = 0|0 ∧ 1 = 0|1 ∧ 1 = 1 |0 ∧ 0 = 0|

<iframe height="800px" width="100%" src="https://repl.it/@DevOpsNinja/ThinWeepyGraphics?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>



### OR | Disjunction

**OR** expressions are denoted with the symbol `∨`.

a ∨ b = a or b

Either a or b must be true in order for an **OR** statement to be true.

|1 ∨ 0 = 1|0 ∨ 1 = 1|1 ∨ 1 = 1|0 ∨ 0 = 0 |

<iframe height="800px" width="100%" src="https://repl.it/@DevOpsNinja/UnequaledCuteMethod?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>



### NOT | Negation

*NOT expressions are denoted with the symbols `¬` or `~`.

If a = 1 then ~a = 0 or vice versa

<iframe height="800px" width="100%" src="https://repl.it/@DevOpsNinja/CoralGruesomeRouter?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>



Hold on tight it is about to get a bit more complex trust me we can do this together.

 <iframe src="https://giphy.com/embed/ZeLqYIfV6RvnptvRti" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/loaf-loof-and-timmy-ZeLqYIfV6RvnptvRti">via GIPHY</a></p>



### Exclusive OR | Exclusive Disjunction | XOR

***Exclusive OR*** expressions are denoted with the symbols `⊕` or `⊻`.

The or exclusivity refers to:

* a or b but not a and b . They can never be both true at the same time.

|1 ⊻ 0 = 1| 0 ⊻ 1= 1|1 ⊻ 1= 0| 0 ⊻ 0 = 0|

If this leaves you a bit confused try this XOR sandbox [http://xor.pw/](http://xor.pw/) you will understand it in no time.

<iframe height="800px" width="100%" src="https://repl.it/@DevOpsNinja/StrangeGrowingEvents?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>



### NAND 

***NAND*** is a contraction of not and , meaning its result will always be the opposite of its ***AND*** expression. ***NAND*** is defined with the symbol `↑` .

a ↑ b = ~(a ∧ b)

|1 ↑ 0 = 1| 0 ↑ 1= 1|1 ↑ 1= 0| 0 ↑ 0= 1|

<iframe height="800px" width="100%" src="https://repl.it/@DevOpsNinja/QuarterlyWordyInitialization?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

### Implies | Conditional

As the name indicates there is a condition involved. Meaning if “If A then B” or “A implies B”. Implies are denoted with the symbol → .

|0 → 0 = 1| 0 → 1 = 1|1 → 1 = 1|1 → 0 = 0|

<iframe height="800px" width="100%" src="https://repl.it/@DevOpsNinja/SpecificVapidGigabyte?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>



### If and Only If | Biconditional

A **biconditional** is a connective that represents the condition “if and only if”, by checking is both propositions have the same value. **Biconditionals** are denoted with the symbol *↔ .

A ↔ B = (A → B) ∧ (B → A)

|0 ↔ 0 = 1| 0 ↔ 1 = 0|1 ↔ 1 = 1|1 ↔ 0 = 0|

<iframe height="800px" width="100%" src="https://repl.it/@DevOpsNinja/DryEarlyBlogs?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>



## Conclusion

Mathematical notation does not have to be complicated as you have seen. Now I leave it up to you as a challenge to try and create your own expressions and test them.

In case you are a Python developer try and create small algorithms using **Propositional Logic Notation**.

## Bibliography

[**Propositional Logic | Brilliant Math & Science Wiki**](https://brilliant.org/wiki/propositional-logic/)

[**Propositional calculus**](https://en.wikipedia.org/wiki/Propositional_calculus)



## Other Links on mathematical notation with Python

[**Mathematical Notation for Python Developers (Part 1)**](https://medium.com/datadriveninvestor/mathematical-notation-for-python-developers-part-1-1c94599b97cd)


[**Mathematical Notation for Python Developers (Part 2) | Sets continuation**](https://medium.com/datadriveninvestor/mathematical-notation-for-python-developers-part-2-sets-continuation-b53cac11a770)






