---
title: Язык разметки Markdown
subtitle: Расскажу базовые сведения о Markdown

# Summary for listings and search engines
summary: Начало работы с Git

# Link this post with a project
projects: []

# Date published
date: '2024-03-28T00:00:00Z'

# Date updated
lastmod: '2024-03-28T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
tags:
  - Markdown

categories:
  - Markdown
---

## Оформление текста

Чтобы создать заголовок, используйте знак #, например:

один знак #
# This is heading 1
два знака #
## This is heading 2
три знака #
### This is heading 3
четыре знака #
#### This is heading 4



Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:
This text is **bold**.

Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:
This text is *italic*.

Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные
звездочки:
This is text is both ***bold and italic***.

Блоки цитирования создаются с помощью символа >:
> The drought had lasted now for ten million years

Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:
- List item 1
- List item A
- List item B
- List item 2

Синтаксис Markdown для встроенной ссылки состоит из части [link text], представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла, на который
дается ссылка:

[ link text ] (file-name.md)

Markdown поддерживает как встраивание фрагментов кода в предложение, так и их размещение между предложениями в виде отдельных огражденных блоков. Огражденные блоки
кода — это простой способ выделить синтаксис для фрагментов кода. Общий формат огражденных блоков кода в ```: 

``` language
your code goes in here
```


