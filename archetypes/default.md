---
title: {{ replaceRE "[0-9]{2,}" "" .Name | replaceRE "^-*" "" | replaceRE "-" " " | title }}
date: {{ .Date }}
lastmod:
author: Willian Nascimento

description:
categories: []
tags: []

draft: true
enableDisqus : false
enableMathJax: false
toc: false
---