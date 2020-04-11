---
template: post
title: Demystifying Git Internal Like A Pro
slug: lsaidhsai
draft: true
date: 2020-04-05T12:44:32.170Z
description: Git for beginners
category: "Tech"
tags:
  - "Python"
  - "Mathematics"
  - "Mathematical Notation with Python"
  - "Mathematics tutorial"
---


![Photo by [Qijin Xu](https://unsplash.com/@obkim?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)](https://cdn-images-1.medium.com/max/12000/0*msUDFngFpw93AzHi)

## Preface



## Prerequisites



## Who Is This Article For
posts/Elementary-Guide-to-Hashicorp-Nomad-with-Linuxnow that there’s more than one way to solve a performance problem. 

While this book is primarily aimed at people with CPU-bound problems, we also look at data transfer and memory-bound solutions. Typically these problems are faced by scientists, engineers, quants, and academics. 

We also look at problems that a web developer might face, including the movement of data and the use of just-in-time (JIT) compilers like PyPy for easy-win performance gains.

It might help if you have a background in C (or C++, or maybe Java), but it isn’t a pre-requisite. Python’s most common interpreter (CPython — the standard you normally get if you type python at the command line) is written in C, and so the hooks and libraries all expose the gory inner C machinery. There are lots of other techniques that we cover that don’t assume any knowledge of C. You might also have a lower-level knowledge of the CPU, memory architecture, and data buses, but again, that’s not strictly necessary.

## Roadmap

* Version Control

* Why do we need Version Control

* What is GIT

* GIT vs The World

* 

## Introduction

Existentialism is a philosophical movement that puts emphasis on individual existence, freedom, and choice. The works inspired by this movement are focused on characters who fight versus society i.e. people who find it difficult to be themselves in society that despises everything that’s different or extraordinary. Numerous painters, philosophers, and writers have flourished under the idea of existentialism and they depict the struggle of a one-man, individual, in the fight versus flawed society, but nobody did it better than Franz Kafka. This essay will focus on Kafka’s life that shaped his greatest, existentialist, works.

So get your headphones, turn on the synthwave and let’s get started.

## Version Control

// Add more in-depth explanation.

Before we understand GIT we must figure out what is version control about.

Version Control also known as revision control or source control is the management of changes in documents. Any performed change will be index by a timestamp and the person who made the change to those documents.

## Why does Version Control even exist in the first place?

Imagine you are working on a collaborative project codebase and beside you, there are other 3000 people involved in it too.

* How are you gonna keep track of changes done in a codebase where 3000 people work at?

* How can you avoid your code from overlapping with the code of others?

* There is someone adding horrible code to your project, how can you find that person?

* Someone added a bug, now the whole application is down, how can you revert the code responsible for this bug?

## What is GIT?

According to their own website:
>  *Git is a free and open-source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.*

Without all that mambo-jambo Git is a simple key-value database.

You can throw any kind of content into it, directories will be known as trees and files as blobs. 

Once you add content into a Git repository, it will hash that content and gzip it while creating a hash key at the time. That hash key will be used to find the right value within the database.


## Git vs The World

Git is not the only distributed version control system (DVCS) out there. Some of the most known alternatives are:
* Mercurial
* SVN (Apache Subversion)
* Monotone
* Bazaar

## Starting With The Basics



## Demystifying The Insides

// Explanation of each file created when a git repository is created

**Description** file: Git generates a file named description which contains the name of the repository as set by the user. It is located at .git/description. It has a default value as an unnamed repository and the developers should place the actual project name and description in this file. It is used by Git as a default way to know the name of the repository.

It is used by GitWeb and is not considered by GitHub or GitLab.
GitWeb is a web interface for git projects. It can be used to generate a web application with search feature, RSS feed and many others. It can be seen as a native alternative to external services like GitHub.


**Objects** folder: Here is where the all the files and directories that you change across time will be stored.
![s](/media/data-model-1.png)

## Afterword



## Acknowledgments



## Notes
