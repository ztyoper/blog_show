---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: "{{ .Date }}"
slug: "{{ .File.ContentBaseName | title }}"
draft: false
categories:
  - "{{ (path.Base .File.Dir) }}"
---
