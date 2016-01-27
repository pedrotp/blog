---
layout: post
title:  "Delegated Event Listeners with jQuery"
date:   2016-01-26 22:56:06 -0500
categories: learning to code
---

In my first couple of months writing code for the web, something I've found myself doing a lot is dynamically generating DOM elements with Javascript. This works well when you load a page with a certain group of elements, but then want to add or remove some of them without reloading the page to, say, remove an input field once it has been submitted, or show the user new messages or alerts. Sometimes though, we want to use these dynamically generated DOM elements as inputs. For example, let's consider this use case: 

