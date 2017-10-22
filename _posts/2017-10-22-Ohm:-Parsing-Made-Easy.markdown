---
layout: post
title: Ohm&#58; Parsing Made Easy
source: https://nextjournal.com/dubroy/ohm-parsing-made-easy
category: HackerNews
description: SiteLog - Ohm&#58; Parsing Made Easy
numwords: 2344
hnscore: 
---

is a parser generator for JavaScript, which was created at to support our programming language research. We think of it as a  that lets you quickly prototype new languages and experiment with extensions to existing languages. You can use Ohm to parse custom file formats or quickly build parsers, interpreters, and compilers for programming languages. In this article, we'll introduce the basic features of Ohm by creating a simple arithmetic language and writing an interpreter for that language. When we're done, we'll have a desktop calculator that can evaluate expressions like The quickest way to use Ohm in the browser is to load it directly from , by adding the following script tag to your page:Under Node.js, you'll first need to install the  to load the Ohm module into your script:Ohm consists of two parts: a domain-specific language, and a library. The  (PEGs), which are a formal way of describing syntax, similar to regular expressions and context-free grammars. The  provides a JavaSc...

![](https://cdn.nextjournal.com:443/data/12200EB5CFA8289D945464ED0ED0E015C3825639CE7E55F9569A57D8089221C13B09)
<!--description-->