---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }} # Date of post creation.
description: "Article description."
featured: true 
draft: true
toc: false 
# menu: main
featureImage: "/images/{{ .Name }}.png" 
thumbnail: "/images/{{ .Name }}.png"
shareImage: "/images/{{ .Name }}.png"
codeMaxLines: 10 
codeLineNumbers: false 
figurePositionShow: true 
categories:
  - Technology
tags:
  - Tag_name1
  - Tag_name2
# comment: false # Disable comment if false.
---

<!--more-->