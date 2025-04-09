---
layout: book_toc
title: Character Prefix Conditioning
description: A clever algorithm for more accurate code completion sampling.
cover_image: /assets/images/books/book1-cover.jpg
author: Jacob
author_image: /assets/images/authors/jacob.jpg
category: Programming
reading_time: 2
featured: true
book_id: book-1
chapters:
  - title: Introduction
    excerpt: Getting started with the basics
    url: /books/book-1/chapter-1
    reading_time: 10
  - title: Advanced Concepts
    excerpt: Taking it to the next level
    url: /books/book-1/chapter-2
    reading_time: 15
---

# {{ page.title }}

Welcome to My First Book. This book will guide you through important concepts and practical examples.

## Table of Contents

{% for chapter in page.chapters %}

1. [{{ chapter.title }}]({{ chapter.url }})
   {{ chapter.excerpt }}
   {% endfor %}
